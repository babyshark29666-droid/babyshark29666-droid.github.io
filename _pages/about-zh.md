---
permalink: /zh/
title: ""
description: "赵淑媛，广州大学统计学本科生，关注统计推断、数据建模与机器人控制。"
author_profile: true
lang: zh-CN
---

# 关于我

我是**广州大学统计学本科生赵淑媛**，预计2027年7月毕业。我的研究经历涵盖未知背景下的 Poisson 精确推断，以及基于纵向数据的中老年人健康风险建模。我关注数学与计算方法如何应用于真实问题。

在机器人控制实习中，我参与了六轴机械臂的**导纳与阻抗控制**开发，以及从 MuJoCo 仿真到 ELFIN10 真机的迁移验证。我已确认可入读**香港科技大学（广州）Redbird MPhil**，预计2027年9月入学。

[英文简历 PDF]({{ '/files/Zhao_Shuyuan_CV.pdf' | relative_url }}) · [English]({{ '/' | relative_url }})

# 教育背景

<div class="education-list">
  <div class="education-entry">
    <a class="education-logo" href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="访问香港科技大学广州官网">
      <img src="{{ '/images/universities/hkust-gz-logo.png' | relative_url }}" alt="香港科技大学广州标识" width="68" height="68" loading="lazy">
    </a>
    <div class="education-details">
      <h3 class="education-school"><a href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer">香港科技大学（广州）<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
      <p class="education-degree">Redbird MPhil</p>
      <p class="education-note">已确认可入读 · 预计2027年9月入学</p>
    </div>
    <p class="education-dates">2027年9月—2029年7月<br><span>预计</span></p>
  </div>
  <div class="education-entry">
    <a class="education-logo" href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="访问广州大学官网">
      <img src="{{ '/images/universities/gzhu-mark.png' | relative_url }}" alt="广州大学校徽" width="68" height="68" loading="lazy">
    </a>
    <div class="education-details">
      <h3 class="education-school"><a href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer">广州大学<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
      <p class="education-degree">统计学本科</p>
      <p class="education-note">预计2027年7月毕业</p>
    </div>
    <p class="education-dates">2023年9月—2027年7月<br><span>预计毕业</span></p>
  </div>
</div>

# 论文

**Dynamic truncation and the Berger–Boos corrected h–function method for optimal exact Poisson confidence intervals with unknown backgrounds**<br>
Lu, H., & **Zhao, S.**<br>
*Computational Statistics 在审稿件。*

针对弱信号与未知背景下的稀有事件数据开展精确 Poisson 推断研究，结合动态截断、Berger–Boos 校正与 h-function，比较区间覆盖率和效率，并应用于 KARMEN 中微子探测数据。

# 研究经历

### 未知背景下的 Poisson 精确推断
*研究成员 · 2025年9月至2026年4月*

- 研究弱信号与未知背景条件下的稀有事件推断，应用背景包括高能物理与生物医学检测。
- 参与结合 Poisson 分位数、Berger–Boos 校正与 h-function 的动态截断方法研究。
- 通过仿真实验，对比 Bayesian、IM、NIM 方法下初始、一次改进和最优精确置信区间的覆盖率与效率。

### 中老年人健康风险的多维量化与纵向分析
*项目负责人 · 2025年3月至5月*

- 负责选题、研究框架与建模策略，结合随机森林、XGBoost 特征筛选，以及固定效应和 GEE 模型开展分析。
- 基于 CHARLS 三期共21,000余条纵向记录，构建6,800余个建模样本。
- 从26项指标中识别12项关键衰弱预测因素，形成涵盖心理健康、身体活动、经济条件、认知功能与医疗服务的五维风险框架。
- 分析不同年龄群体中主导风险因素的变化，为分层干预与社区健康规划提供建议。

# 机器人控制项目

**东莞市新佰人机器人科技有限责任公司 — 控制算法部门**<br>
*强化学习助理工程师实习 · 2026年6月至9月*

### 六轴机械臂笛卡尔空间导纳控制

- 建立质量—阻尼—刚度导纳模型，将末端外力转换为笛卡尔空间位置和速度修正量，面向接触作业、表面跟随与人机交互场景实现柔顺响应。
- 将导纳修正叠加至直线或圆弧名义轨迹，搭建外力采集、导纳求解、位姿修正、逆运动学与 PD 力矩控制链路，并加入位移、速度和力矩限幅。
- 完成 MuJoCo 仿真到 ELFIN10 真机的迁移，统一运动学模型、控制周期和数据接口，通过 CODESYS 与 TCP 通信完成参数标定与真机验证。

### 六轴机械臂关节空间阻抗控制

- 基于关节位置和速度误差计算阻抗力矩，兼顾轨迹跟踪与外部阻挡下的柔顺响应。
- 结合 Pinocchio 动力学模型进行重力、科氏力与摩擦补偿，并加入软启动、力矩限幅和失联保护。
- 完成仿真到真机迁移，统一关节顺序、零位偏置、单位与力矩方向，完成 CST 力矩控制及真机轨迹验证。

# 其他项目

### 可持续旅游优化建模
*团队成员，负责报告写作与建模分析 · 2025年1月*

整合文献与多源数据，构建 DPSIR 指标体系，将旅游承载量、生态、基础设施与居民影响之间的权衡转化为非线性优化问题；组织报告结构、展示遗传算法结果，并开展 Juneau 与西安的对比分析。

### 高熵合金性能预测平台商业化方案
*技术商业化与商业计划负责人 · 2025年4月至8月*

将机器学习辅助高熵合金性能预测平台的技术内容转化为面向航空航天与高端制造的产品方案，开展市场分析，整合技术、营销、财务与法律信息形成商业计划书。

### 佛山祖庙武术研学课程设计
*项目负责人 · 2025年10月至2026年4月*

组织访谈、现场观察和问卷调研，基于815份有效问卷开展聚类与结构方程分析，研究文化认知与公众参与之间的差距，形成五类访客画像和四个课程模块。

# 荣誉奖项

- **2025年** — 全国大学生统计建模大赛广东赛区一等奖。
- **2025年** — 正大杯全国大学生市场调查与分析大赛国家三等奖。
- **2025年** — 美国大学生数学建模竞赛 MCM/ICM，Honorable Mention。
- 广州大学一等奖学金。

# 技术能力

- **编程与工具：** Python、R、Linux、Git、CODESYS。
- **统计与数据分析：** 统计建模、纵向数据分析、机器学习、问卷数据分析，NumPy、Pandas、Matplotlib。
- **机器人技术：** MuJoCo、Pinocchio、导纳控制、阻抗控制、PD/PID 与动力学补偿。
- **语言：** 普通话母语，英语 IELTS 6.5。

# 补充经历

- **日本上智大学短期项目，2025年7月。** 在国际交流环境中参与可持续发展主题的英文小组展示。
- **易班云陪伴志愿辅导，2023年10月至2024年12月。** 为小学生提供周末数学辅导与持续陪伴。
