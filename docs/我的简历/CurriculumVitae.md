---
title: My CV
sticky: 1
createTime: 2025/07/09 00:06:14
permalink: /article/37q75frh/
---
::: demo-wrapper title="我的简历" no-padding height="100%"
<style scoped>
  .resume-container {
    color: #000000;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    max-height: 100%;
    overflow-y: auto;
    padding: 20px;
    background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  }

  p {
    color: #000000;
  }

  span {
    color: #000000;
  }

  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 10px;
    padding-bottom: 15px;
  }

  .profile-img {
    width: 120px;
    height: 160px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-weight: bold;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  }

  .personal-info {
    flex: 1;
    color: #000000;
    padding-left: 20px;
  }

  .name {
    font-size: 28px;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 5px;
  }

  .contact-info {
    color: #000000;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 10px;
  }

  .contact-item {
    display: flex;
    align-items: center;
    font-size: 14px;
    color: #34495e;
  }

  .contact-item i {
    margin-right: 5px;
    color: #3498db;
  }

  .basic-info {
    color: #000000;
    display: flex;
    gap: 10px;
    font-size: 14px;
    margin-top: 15px;
  }

  .section {
    color: #000000;
    margin-bottom: 25px;
  }

  .section-title {
    font-size: 20px;
    font-weight: bold;
    color: #2c3e50;
    padding-bottom: 8px;
    border-bottom: 2px solid #3498db;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
  }

  .section-title i {
    margin-right: 10px;
    color: #3498db;
  }

  .col-wrap {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    color: #000000;
  }

  @media (max-width: 768px) {
    .col-wrap { 
      grid-template-columns: 1fr; 
    }
  }

  .item {
    color: #000000;
    background: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
    margin-bottom: 15px;
    transition: transform 0.3s ease;
  }

  .item:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  }

  .item-header {
    color: #000000;
    display: flex;
    justify-content: space-between;
    margin-bottom: 8px;
  }

  .item-title {
    font-weight: bold;
    color: #2c3e50;
    font-size: 16px;
  }

  .item-subtitle {
    color: #3498db;
    font-size: 15px;
  }

  .item-date {
    color: #7f8c8d;
    font-size: 13px;
    font-style: italic;
  }

  .item-content {
    font-size: 14px;
    color: #34495e;
  }

  .star-rating {
    color: #f39c12;
    margin-top: 5px;
  }

  .skills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 10px;
  }

  .skill-tag {
    background: #55b6f6;
    color: white;
    padding: 5px 10px;
    border-radius: 20px;
    font-size: 12px;
  }

  .sar-item {
    margin-bottom: 10px;
    color: #000000;
  }

  .sar-title {
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 5px;
  }

  .sar-content {
    padding-left: 15px;
    border-left: 2px solid #3498db;
    margin-left: 5px;
    color: #000000;
  }

  .project-feature {
    background: #f8f9fa;
    padding: 10px;
    border-radius: 5px;
    margin: 10px 0;
    color: #000000;
    border-left: 3px solid #3498db;
  }

  .responsibility {
    margin-top: 8px;
    color: #000000;
  }

  .badge {
    display: inline-block;
    padding: 2px 8px;
    border-radius: 10px;
    font-size: 12px;
    font-weight: bold;
    margin-right: 5px;
  }
  .badge-tip {
    background-color: #42b983;
    color: white;
  }
  .badge-warning {
    background-color:rgba(231, 193, 0, 0.78);
    color: white;
  }
  .badge-danger {
    background-color:rgba(245, 108, 108, 0.84);
    color: white;
  }

  @media print {
    .resume-container {
      box-shadow: none;
      padding: 10px;
    }
  }
</style>
<div class="resume-container">
  <!-- 个人信息头部 -->
  <div class="header">
    <div class="personal-info">
      <div class="name">岳兵</div>
      <div class="contact-info" style="margin-top: 10px;">
        <div class="contact-item"><i>📱</i>电话：173-6663-6806</div>
        <div class="contact-item"><i>✉️</i>邮箱：yuebing6806@163.com</div>
        <div class="contact-item"><i>📍</i>现居地：杭州</div>
      </div>
      <div class="basic-info">
        <div>24岁</div>
        <div>女</div>
        <div>在校（26届毕业生）</div>
      </div>
    </div>
    <img class="profile-img" src="/images/myself.jpg"/>
  </div>

  <!-- 教育经历 -->
  <div class="section">
    <div class="section-title"><i>🎓</i>教育经历</div>
    <div class="item">
      <div class="item-header">
        <div class="item-title">杭州电子科技大学</div>
        <div class="item-date">2019年09月 - 2023年06月</div>
      </div>
      <div class="item-subtitle">软件工程 本科 计算机学院 | 杭州</div>
      <div class="item-content" style="margin-top: 5px;">
        <p>学生工作：杭电之声广播电视台外联部部长、计算机学院团委副书记助理</p>
        <p>校园经历：挑战杯大学生创业大赛校一等奖、校三等奖学金、优秀学生干部、优秀共青团干部、优秀志愿者、优秀学生宣传员</p>
      </div>
    </div>
    <div class="item">
      <div class="item-header">
        <div class="item-title">南京师范大学 
          <span class="badge badge-warning">211</span> <span class="badge badge-danger">双一流</span>
        </div>
        <div class="item-date">2023年09月 - 2026年06月</div>
      </div>
      <div class="item-subtitle">现代教育技术 硕士 教育科学学院 | 南京</div>
      <div class="item-content" style="margin-top: 5px;">
        <p>考研成绩：399分（专业第一）</p>
        <p>学生工作：2024-2025年担任校研会博士生工作部部长、校二等奖学金</p>
      </div>
    </div>
  </div>

  <!-- 实习经历 -->
  <div class="section">
    <div class="section-title"><i>💼</i>实习经历</div>
    <div class="item">
      <div class="item-header">
        <div class="item-title">科鲸（杭州）信息技术有限公司（Datawhale AI开源学习社区）</div>
        <div class="item-date">2024年07月 - 2025年07月</div>
      </div>
      <div class="item-subtitle">职位；产品经理实习生</div>
      <div class="sar-item" style="margin-top: 5px;">
        <div class="sar-title">AI Agent产品设计和AI项目探索</div>
        <div class="sar-content">
          <p><strong>背景与驱动:</strong> 基于公司AI开源学习社区的定位发展和我本人探索AI的热情与专业优势，我主动发起并深度参与多个AI项目，致力于用技术推动教育普惠与效率革新。</p>
          <p><strong>行动和结果:</strong></p>
          <ul>
            <li><strong>精灵小舒Agent开发（AI赋能高校思政教育）：</strong> 与上海交大思政老师合作，主导设计基于Coze的学业压力疏解智能体，搭建Agent框架并优化，成果获上海辅导员座谈会示范展示。</li>
            <li><strong>利用低代码平台开发产品Demo（AI赋能产品工作流）：</strong> 利用Coze空间高效完成"高校行活动页"及"AI学习小助手"MVP功能设计与原型开发。将需求到原型输出的时间从数天缩短至半小时内，大幅降低沟通成本，探索出AI赋能产品工作的有效路径，成为团队实践案例。</li>
            <li><strong>AI创新思维课程设计（AI赋能青少年教育）：</strong> 从0-1设计杭州星桥中学AI课程体系（8课时），深度调研学生认知水平与兴趣点，实施创新实践课程，激发学生产出24份创新作品。沉淀标准化课程设计与实施方法论，发表于Datawhale平台，并代表Datawhale向无锡市教育局分享实践经验。</li>
            <li><strong>辅助学员搭建智能体（AI赋能行业落地）：</strong> 担任上海交大安泰经管学院"AI+X"实训营助教，指导20+ (E)MBA学员完成AI工作流搭建，推动实现行业场景技术落地。共建Learning Center，打造可持续项目孵化平台，树立产学研深度合作标杆案例。</li>
            <li><strong>开展AI Agent实践分享活动（AI+人文社科教育）：</strong> 策划并主讲杭州电子科技大学社会学专业"AI Agent实践"线下工作坊，指导学生掌握AI Agent应用技能，培养人机协同创新思维。</li>
          </ul>
          <p><strong>个人总结：</strong> 拥抱AI、具有开源精神，积极参与AI普惠教育活动。热爱用AI技术解决真实场景的真实问题，具备从用户洞察到产品落地的全流程执行力，期待将AI技术与教育创新深度结合。</p>
        </div>
      </div>
      <div class="sar-item">
        <div class="sar-title">AI开源学习平台优化与后台建设（AI社区->AI平台化转型）</div>
        <div class="sar-content">
          <p><strong>背景与任务:</strong> 针对官网存在的功能薄弱、用户体验不佳、用户留存率低、核心业务展示不足，以及后台系统分散导致的运营效率低下等核心痛点，深度参与官网核心功能模块（登录/认证/资讯/首页/个人中心）的产品设计与迭代优化（包含AI功能设计），同时负责支撑后台系统（考试/证书/表单/文章管理）的架构梳理与功能建设。</p>
          <p><strong>行动和结果:</strong></p>
          <ul>
            <li><strong>课程视频AI转录功能：</strong> 通过集成通义API实现视频智能转写、知识点分段及关键词检索，解决纯视频形式课程检索难、知识点回顾效率低，影响用户学习体验与完课率的问题，强化了平台多模态学习体验与AI技术属性。</li>
            <li><strong>认证板块：</strong> 深入分析证书价值与用户需求，设计信息架构与交互流程，规划内容模块（价值主张、认证路径、证书展示、FAQ），绘制高保真原型。累计发证量从2万增至5万+，考证次数超10万，成为官网最大流量入口。</li>
            <li><strong>后台系统提效：</strong> 梳理并设计考试管理、证书管理、表单管理、文章管理，促进运营效率显著提升，发证实现全流程自动化。</li>
          </ul>
          <p><strong>全局成果：</strong> 官网优化驱动平台注册用户量翻4倍，增长近10万。构建的高效前后台体系支撑业务规模翻倍。</p>
        </div>
      </div>
      <div class="sar-item">
        <div class="sar-title">AI学习营活动和"AI+X"高校行活动全流程产品支持（主营业务支持）</div>
        <div class="sar-content">
          <p><strong>背景与任务:</strong> 全面支持公司主营业务（万人级AI学习营活动）高效运转，同时解决"AI+X"高校行活动资源分散、信息不通的核心痛点，通过产品化手段提升整体业务效率与协同能力。</p>
          <p><strong>项目1：AI学习营活动全周期产品支持</strong></p>
          <ul>
            <li><strong>行动：</strong> 主导设计并上线各期活动专题页，支撑活动宣传与用户转化；快速迭代平台产品功能，满足活动运营的即时需求；搭建活动核心数据看板（用户转化漏斗、学习打卡分析、宣传大使数据等），建立数据监测体系。</li>
            <li><strong>结果：</strong> 保障多期万人活动顺畅运行，驱动活动报名转化率平均达80%以上，数据看板搭建有效支撑运营策略调整与教研优化，助力活动成果超额完成业务KPI。</li>
          </ul>
          <p><strong>项目2：高校行活动专题网站从0到1建设</strong></p>
          <ul>
            <li><strong>行动：</strong> 主导需求调研与分析，设计网站信息架构与核心功能模块（活动信息、组织流程、申报入口）；完成产品原型设计，协助运营梳理数据与资料，优化内容呈现方式；协调资源实现网站开发与上线。</li>
            <li><strong>结果：</strong> 从0到1成功上线高校行专题网站，有效沉淀国内外100+所高校活动资源（资料、流程、经验），成为面向高校的核心信息门户与宣传阵地；助力高校行业务实现规模化突破；从依赖单校一对一驻点服务模式，转型为可并发运作的标准化远程支持模式，提升业务覆盖效率10倍+。</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div class="col-wrap">
    <!-- 专业技能 -->
    <div class="section">
      <div class="section-title"><i>💻</i>专业技能</div>
      <div class="item" style="min-height: 400px">
        <div class="item-content">
          <p><strong>原型设计工具：</strong> 精通Figma、墨刀、Xmind、illustrator和飞书等产品常用工具，能够快速高效地完成产品原型设计。</p>
          <p style="margin-top: 15px;"><strong>数据分析工具：</strong> 熟练使用 AI 辅助编写 SQL 语句，深入分析用户数据，为产品决策提供有力支持。</p>
          <p style="margin-top: 15px;"><strong>AI工具：</strong> 熟练使用 Coze、Manus、秒哒、Flowith等AI Agent产品，辅助竞品调研、原型设计和需求文档撰写等工作。</p>
          <p style="margin-top: 15px;"><strong>AI效率工具：</strong> 熟练使用即梦做设计、通义做会议记录、小浣熊做数据分析、秘塔做调研等，全方位提升工作效率。</p>
        </div>
      </div>
    </div> 
    <!-- 其他信息 -->
    <div class="section">
      <div class="section-title"><i>🌟</i>其他</div>
      <div class="item" style="min-height: 400px">
        <div class="item-content">
          <p><strong>证书/执照：</strong></p>
          <ul>
            <li>普通话水平二级甲等</li>
            <li>计算机技术与软件专业技术初级资格证</li>
          </ul>
          <p><strong>语言：</strong></p>
          <ul>
            <li>英语（CET-6）</li>
          </ul>
          <p><strong>兴趣爱好：</strong></p>
          <ul>
            <li>喜欢探索各类AI产品（开发AI燕双鹰接入微信聊天），探索AI落地的可能性</li>
            <li>中国民族舞（10级）</li>
            <li>小提琴</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>
:::