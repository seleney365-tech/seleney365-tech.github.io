---
layout: single
title: "Skills & Activities"
permalink: /skills/
author_profile: true
---

<style>
  /* 两栏布局 */
  .skills-wrapper {
    display: flex;
    gap: 30px;
    align-items: flex-start;
  }
  .skills-main {
    flex: 1;
    min-width: 0;
  }
  .skills-sidebar {
    width: 200px;
    flex-shrink: 0;
    position: sticky;
    top: 80px;
    align-self: flex-start;
  }

  /* 目录 */
  .toc-box {
    background: #f5f8fc;
    border: 1px solid #d0d7de;
    border-radius: 8px;
    padding: 14px 18px;
  }
  .toc-box h4 {
    margin: 0 0 8px 0;
    color: #1a4f8a;
    font-size: 1em;
  }
  .toc-box ul {
    margin: 0;
    padding-left: 18px;
  }
  .toc-box li {
    margin-bottom: 6px;
  }
  .toc-box a {
    color: #2a7ae2;
    text-decoration: none;
    font-size: 0.9em;
  }
  .toc-box a:hover {
    text-decoration: underline;
  }

  /* 卡片 */
  .card-block {
    background: #fafbfd;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 20px 24px;
    margin-bottom: 2em;
  }
  .card-block .block-title {
    color: #2a7ae2;
    font-size: 1.35em;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 1em;
    padding-bottom: 6px;
    border-bottom: 2px solid #2a7ae2;
  }
  .card-block ul {
    margin: 0;
    padding-left: 20px;
  }
  .card-block li {
    font-size: 0.95em;
    line-height: 1.6;
    color: #333;
    margin-bottom: 6px;
  }
  .card-block strong {
    color: #1a4f8a;
  }

  /* 窄屏适配 */
  @media (max-width: 768px) {
    .skills-wrapper {
      flex-direction: column;
    }
    .skills-sidebar {
      width: 100%;
      position: static;
      order: -1;
    }
  }
</style>

<div class="skills-wrapper">

  <!-- 左侧主内容 -->
  <div class="skills-main">

    <div class="card-block" id="technical">
      <h2 class="block-title">💻 Technical Skills</h2>
      <ul>
        <li><strong>Programming Languages:</strong> Python, R, C++, MATLAB</li>
        <li><strong>Statistical &amp; Econometric Software:</strong> Stata, SPSS <em>(able to independently write standard-format papers and reports using these tools)</em></li>
        <li><strong>Database:</strong> SQL</li>
        <li><strong>Document &amp; Typesetting:</strong> LaTeX, Microsoft Office (Word, Excel, PowerPoint)</li>
        <li><strong>Data &amp; Business Tools:</strong> Excel (Advanced), BI Tools</li>
        <li><strong>Version Control:</strong> Git / GitHub</li>
      </ul>
    </div>

    <div class="card-block" id="ai">
      <h2 class="block-title">🤖 AI Tools</h2>
      <ul>
        <li>Proficient in writing effective AI prompts and instructions</li>
        <li>Skilled use of professional AI tools including <strong>ChatGPT</strong>, <strong>Codex</strong>, <strong>Gemini</strong>, and other AI-assisted platforms</li>
      </ul>
    </div>

    <div class="card-block" id="languages">
      <h2 class="block-title">🌏 Languages</h2>
      <ul>
        <li><strong>Mandarin:</strong> Native</li>
        <li><strong>English:</strong> Fluent</li>
        <li><strong>Cantonese:</strong> Basic</li>
      </ul>
    </div>

    <div class="card-block" id="newmedia">
      <h2 class="block-title">🎬 New Media Skills</h2>
      <ul>
        <li>Video Editing</li>
        <li>WeChat Official Account Production</li>
        <li>Copywriting</li>
        <li>Poster Design</li>
        <li>Video Shooting</li>
        <li>Script Writing</li>
      </ul>
    </div>

    <div class="card-block" id="hobbies">
      <h2 class="block-title">🎵 Hobbies, Interests &amp; Volunteer Service</h2>
      <ul>
        <li><strong>Music:</strong> Singing, Piano, French Horn</li>
        <li><strong>Sports:</strong> Badminton, Swimming, Hiking, Mountain Climbing, Running</li>
        <li><strong>Volunteer Service:</strong> <!-- 可补充具体内容，如支教、社区服务、赛事志愿者等 --></li>
      </ul>
    </div>

  </div>

  <!-- 右侧固定目录 -->
  <div class="skills-sidebar">
    <div class="toc-box">
      <h4>Contents</h4>
      <ul>
        <li><a href="#technical">Technical Skills</a></li>
        <li><a href="#ai">AI Tools</a></li>
        <li><a href="#languages">Languages</a></li>
        <li><a href="#newmedia">New Media Skills</a></li>
        <li><a href="#hobbies">Hobbies &amp; Volunteer</a></li>
      </ul>
    </div>
  </div>

</div>
