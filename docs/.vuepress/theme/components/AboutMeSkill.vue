<template>
  <div class="about-me-card-bg vp-blog-post-item about-me-skill">
    <div style="margin-left: 20px">
      <p class="about-me-card-title-normal">技能</p>
      <p class="about-me-card-text-big">我的能力</p>
    </div>
    <!-- 第一行向左移动 -->
    <div class="marquee-row first-row">
      <div class="marquee-content">
        <span v-for="(item, index) in technology" :key="index"> <icon :name="item.icon" /> </span>
        <span v-for="(item, index) in technology" :key="index + technology.length"><icon :name="item.icon" /></span>
      </div>
    </div>
    <!-- 第二行向右移动 -->
    <div class="marquee-row second-row">
      <div class="marquee-content">
        <span v-for="(item, index) in tools" :key="index"><icon :name="item.icon" /></span>
        <span v-for="(item, index) in tools" :key="index + tools.length"><icon :name="item.icon" /></span>
      </div>
    </div>

    <div class="about-me-skill-detail">
      <span v-for="(item, index) in technology" :key="index"> <icon :name="item.icon" /> <span>{{item.type}}</span>  </span>
      <span v-for="(item, index) in tools" :key="index"><icon :name="item.icon" /> <span>{{item.type}}</span> </span>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

// 技能
const technology = ref([
  { type: '墨刀', icon: '/skills/墨刀.svg' },
  { type: 'VSCode', icon: '/skills/vscode.svg' },
  { type: 'Figma', icon: '/skills/Figma.svg' },
  { type: 'Xmind', icon: '/skills/xmind.svg' },
  { type: '腾讯元宝', icon: '/skills/yuanbao.svg' },
  { type: '豆包', icon: '/skills/doubao.svg' },
  { type: 'Gemini', icon: '/skills/gemini.svg' },
    { type: '即梦', icon: '/skills/即梦.svg' },
]);

// 工具
const tools = ref([
  { type: 'Deepseek', icon: '/skills/deepseek.svg' },
  { type: 'Coze', icon: '/skills/Coze.svg' },
  { type: 'Manus', icon: '/skills/manus.svg' },
  { type: '飞书', icon: '/skills/lark.svg' },
  { type: '秒哒', icon: '/skills/秒哒.png' },
  { type: '即时设计', icon: '/skills/即时设计.svg' },
  { type: 'Adobe', icon: '/skills/adobe.svg' },
  { type: 'ChatGPT', icon: '/skills/chatgpt.svg' },
  { type: 'Cursor', icon: '/skills/cursor.webp' },
]);
</script>

<style scoped>
.about-me-skill{
  position: relative;
  min-height: 316px;
  padding: 20px 0;
  z-index: 1;
  &:hover .marquee-row{
    opacity: 0;
  }
  &:hover .about-me-skill-detail{
    opacity: 1;
  }
}

.about-me-skill-detail{
  position: absolute;
  top: 100px;
  opacity: 0;
  z-index: 2;
  display: flex;
  padding: 0 20px;
  transition: opacity 0.5s;
  flex-wrap: wrap;
  >span{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 6px 6px 0;
    border-radius: 8px;
    padding: 7px;
    font-size: 16px;
    color: var(--vp-c-text-2);
    background-color: var(--home-action-bnt-bg);
  }
}

.marquee-row {
  transition: opacity 0.6s 0.1s;
  width: 105%;
  margin-left: -6px;
  overflow: hidden;
  white-space: nowrap;
  transform: rotateZ(-6deg);
}

.marquee-content {
  display: inline-flex;
  animation: marquee-left 30s linear infinite;
  >span{
    border-radius: 20%;
    align-content: center;
    align-items: center;
    background-color: var(--about-me-skill-item-bg);
    width: 80px;
    height: 80px;
    font-size: 50px;
    margin: 0 10px;
  }

}
.first-row{
  margin-top: 20px;
}
.second-row{
  margin-top: 20px;
}
.second-row .marquee-content {
  animation: marquee-right 50s linear infinite;
}

@keyframes marquee-left {
  0% { transform: translateX(0%); }
  100% { transform: translateX(-50%); }
}

@keyframes marquee-right {
  0% { transform: translateX(-50%); }
  100% { transform: translateX(0%); }
}
</style>
