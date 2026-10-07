---
layout: single
title: "Academic"
permalink: /academic/
author_profile: true
---

<style>
  /* 两栏布局 */
  .acad-wrapper {
    display: flex;
    gap: 30px;
    align-items: flex-start;
  }
  .acad-main {
    flex: 1;
    min-width: 0;
  }
  .acad-sidebar {
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

  /* 学校大卡片 */
  .school-card {
    background: #fafbfd;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 22px 26px;
    margin-bottom: 2em;
  }
  .school-card .school-title {
    color: #2a7ae2;
    font-size: 1.4em;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 0.2em;
  }
  .school-card .school-meta {
    color: #666;
    font-size: 0.9em;
    margin-bottom: 1.2em;
  }

  /* 课程分类小卡片 */
  .course-group {
    background: #ffffff;
    border-left: 4px solid #2a7ae2;
    border-radius: 6px;
    padding: 14px 18px;
    margin-bottom: 1.5em;
  }
  .course-group .group-title {
    color: #1a4f8a;
    font-size: 1.1em;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 1em;
    border-bottom: 1px dashed #c8d6e5;
    padding-bottom: 6px;
  }

  /* 课程条目 */
  .course-item {
    margin-bottom: 1em;
  }
  .course-item strong {
    color: #1a4f8a;
    font-size: 1.02em;
  }
  .course-item p {
    margin: 2px 0 0 0;
    color: #333;
    font-size: 0.95em;
    line-height: 1.5;
  }

  /* 窄屏适配 */
  @media (max-width: 768px) {
    .acad-wrapper {
      flex-direction: column;
    }
    .acad-sidebar {
      width: 100%;
      position: static;
      order: -1;
    }
  }
</style>

<div class="acad-wrapper">

  <!-- 左侧主内容 -->
  <div class="acad-main">

    <!-- HKUST -->
    <div class="school-card" id="hkust">
      <h2 class="school-title">🎓 The Hong Kong University of Science and Technology</h2>
      <p class="school-meta">MSc in Economics · Aug 2026 – Aug 2027 (expected)</p>

      <div class="course-group">
        <h3 class="group-title">📘 Master's Courses</h3>

        <div class="course-item">
          <strong>Advanced Macroeconomics</strong>
          <p>Advanced macroeconomic theory, including dynamic general equilibrium models, growth theory, business cycle analysis, and the role of fiscal and monetary policy in modern economies.</p>
        </div>

        <div class="course-item">
          <strong>Advanced Microeconomics</strong>
          <p>Advanced microeconomic theory covering consumer and producer theory, general equilibrium, game theory, mechanism design, and information economics.</p>
        </div>

        <div class="course-item">
          <strong>Advanced Econometrics</strong>
          <p>Advanced econometric methods for empirical research, including panel data models, instrumental variables, maximum likelihood estimation, and causal inference techniques.</p>
        </div>

        <div class="course-item">
          <strong>Corporate Finance</strong>
          <p>Corporate valuation, capital structure decisions, dividend policy, mergers and acquisitions, and investment decision-making under uncertainty.</p>
        </div>

        <div class="course-item">
          <strong>FinTech</strong>
          <p>Financial technology and innovation, including digital payments, blockchain, stablecoins, robo-advisors, and the application of data science in modern financial services.</p>
        </div>
      </div>
    </div>

    <!-- GDUFS -->
    <div class="school-card" id="gdufs">
      <h2 class="school-title">🎓 Guangdong University of Foreign Studies</h2>
      <p class="school-meta">BSc in Economics (Economic Statistics) · Sep 2022 – Jun 2026</p>

      <div class="course-group">
        <h3 class="group-title">📗 Core Courses in Economics</h3>

        <div class="course-item">
          <strong>Microeconomics</strong>
          <p>Consumer behavior, firm production, market structures, pricing, and welfare economics.</p>
        </div>
        <div class="course-item">
          <strong>Macroeconomics</strong>
          <p>National income accounting, economic growth, inflation, unemployment, and fiscal and monetary policy.</p>
        </div>
        <div class="course-item">
          <strong>Political Economy</strong>
          <p>Marxist political economy, commodity and value theory, capital accumulation, and the socialist market economy.</p>
        </div>
        <div class="course-item">
          <strong>Public Economics</strong>
          <p>Government taxation, public expenditure, public goods, externalities, and welfare analysis.</p>
        </div>
        <div class="course-item">
          <strong>Econometrics</strong>
          <p>Linear regression, hypothesis testing, endogeneity, instrumental variables, and empirical applications in economics.</p>
        </div>
        <div class="course-item">
          <strong>Statistics</strong>
          <p>Descriptive statistics, probability distributions, sampling, estimation, and hypothesis testing.</p>
        </div>
        <div class="course-item">
          <strong>Probability Theory</strong>
          <p>Probability spaces, random variables, expectation, conditional probability, and limit theorems.</p>
        </div>
        <div class="course-item">
          <strong>Multivariate Statistical Analysis</strong>
          <p>Multivariate normal distribution, principal component analysis, factor analysis, and cluster analysis.</p>
        </div>
        <div class="course-item">
          <strong>Time Series Analysis</strong>
          <p>Stationarity, ARIMA models, unit root tests, cointegration, and economic forecasting.</p>
        </div>
        <div class="course-item">
          <strong>Modern Regression Analysis</strong>
          <p>Multiple regression, model diagnostics, heteroskedasticity, and generalized linear models.</p>
        </div>
        <div class="course-item">
          <strong>Non-parameter Statistics</strong>
          <p>Kernel density estimation, non-parametric regression, and smoothing methods without distributional assumptions.</p>
        </div>
        <div class="course-item">
          <strong>Sampling Technology</strong>
          <p>Sampling designs, stratified sampling, cluster sampling, and survey data analysis.</p>
        </div>
        <div class="course-item">
          <strong>Statistical Models</strong>
          <p>Generalized linear models, logistic regression, Poisson regression, and model selection.</p>
        </div>
        <div class="course-item">
          <strong>Market Research and Forecasting</strong>
          <p>Market survey design, consumer behavior analysis, demand forecasting, and business applications.</p>
        </div>
        <div class="course-item">
          <strong>Mathematical Statistics</strong>
          <p>Estimation theory, sufficient statistics, hypothesis testing theory, and asymptotic properties.</p>
        </div>
      </div>

      <div class="course-group">
        <h3 class="group-title">📐 Core Courses in Mathematics &amp; Programming</h3>

        <div class="course-item">
          <strong>Advanced Mathematics (I &amp; II)</strong>
          <p>Calculus, limits, derivatives, integrals, series, and multivariable calculus.</p>
        </div>
        <div class="course-item">
          <strong>Advanced Algebra</strong>
          <p>Linear algebra, matrices, determinants, eigenvalues, and vector spaces.</p>
        </div>
        <div class="course-item">
          <strong>Python Programming</strong>
          <p>Python syntax, data structures, file handling, and basic data analysis libraries.</p>
        </div>
        <div class="course-item">
          <strong>R Programming Language</strong>
          <p>R syntax, data manipulation, statistical analysis, and visualization.</p>
        </div>
        <div class="course-item">
          <strong>C++ Programming Language</strong>
          <p>C++ syntax, object-oriented programming, algorithms, and data structures.</p>
        </div>
        <div class="course-item">
          <strong>Database Technology</strong>
          <p>Relational databases, SQL queries, data modeling, and database design.</p>
        </div>
        <div class="course-item">
          <strong>Data Management and Analysis in MS Excel</strong>
          <p>Excel functions, pivot tables, data cleaning, and basic statistical analysis.</p>
        </div>
        <div class="course-item">
          <strong>Data Mining Operation</strong>
          <p>Data preprocessing, classification, clustering, association rules, and predictive modeling.</p>
        </div>
      </div>

      <div class="course-group">
        <h3 class="group-title">📙 Other Relevant Courses</h3>

        <div class="course-item">
          <strong>Accounting</strong>
          <p>Financial accounting principles, financial statements, and basic managerial accounting.</p>
        </div>
        <div class="course-item">
          <strong>Money and Banking</strong>
          <p>Financial systems, central banking, monetary policy, and the role of financial intermediaries.</p>
        </div>
        <div class="course-item">
          <strong>International Trade</strong>
          <p>Comparative advantage, trade theories, trade policy, and global economic integration.</p>
        </div>
        <div class="course-item">
          <strong>Corporate Operations Statistics</strong>
          <p>Statistical methods for business operations, quality control, and process improvement.</p>
        </div>
        <div class="course-item">
          <strong>Statistical Software</strong>
          <p>Practical use of statistical software (SPSS, Stata) for data analysis.</p>
        </div>
        <div class="course-item">
          <strong>Innovation and Entrepreneurial Basics</strong>
          <p>Fundamentals of innovation, business model design, and entrepreneurship.</p>
        </div>
      </div>
    </div>

  </div>

  <!-- 右侧固定目录 -->
  <div class="acad-sidebar">
    <div class="toc-box">
      <h4>Contents</h4>
      <ul>
        <li><a href="#hkust">HKUST</a></li>
        <li><a href="#gdufs">GDUFS</a></li>
      </ul>
    </div>
  </div>

</div>
