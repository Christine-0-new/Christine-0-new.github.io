<template>
  <div class="container">
    <div class="header">
      <div class="head-social">
        <router-link to="/blog/" class="head-social-avatar"><img src="/xixi.jpg" alt="avatar"></router-link>
      </div>
      <img src="/images/welcome2.svg" alt="welcome">
    </div>
    <div class="about-me">

      <div class="card-content grid-row-3-2">
        <AboutMeSkill/>
        <AboutMeAbility/>
      </div>
      <div class="card-content grid-row-1-1">
        <AboutMeText>
          <template #motto>
            <slot name="motto">
              <p class="about-me-card-title-normal">追求</p>
              <p class="about-me-card-text-big">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;和<span style="color: #3a79cc">有趣的人</span>
              </p>
              <p class="about-me-card-text-big">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一起做<span style="color: #f84d4d">有意义的事</span></p>
            </slot>
          </template>
        </AboutMeText>
        <AboutMeCharacter/>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  z-index: 1;
  width: 100%;
  height: 100%;
  padding-bottom: 50px;
  background-color: rgba(240, 222, 201, 0.25);
  overflow-x: hidden !important;
  overflow-y: hidden !important;
}

canvas {
  z-index: -1;
  position: fixed;
  top: -1px;
  left: -1px;
  pointer-events: none; /* 允许鼠标事件穿透 */
  overflow: hidden;
}
.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.head-social {
  display: flex;
  width: fit-content;
  margin: 0 auto;
  align-items: center;

  .head-social-avatar {
    margin: 10px;
    border-radius: 50%;
    width: 80px;
    overflow: hidden;
    transition: transform 0.2s;

    &:hover {
      transform: scale(1.1);
    }
  }
}

.about-me {
  max-width: 1380px;
  margin: 0 auto;
  width: 90%;
  @media screen and (max-width: 770px) {
    width: 94%;
  }
}

.card-content{
  margin-top: 20px;
  display: grid;
  gap: 20px;
  @media screen and (max-width: 770px) {
    display: flex;
    flex-direction: column;
  }
}
.grid-row-2-3 {
  grid-template-columns: 2fr 3fr;
}
.grid-row-3-2 {
  grid-template-columns: 3fr 2fr;
}

.grid-row-1-1 {
  grid-template-columns: 1fr 1fr;
}

</style>


<script setup lang="ts">
import AboutMeText from "./AboutMeText.vue";
import AboutMeSkill from "./AboutMeSkill.vue";
import AboutMeCharacter from "./AboutMeCharacter.vue";
import AboutMeAbility from "./AboutMeAbility.vue";
</script>


