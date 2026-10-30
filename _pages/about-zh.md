---
permalink: /zh/
title: ""
description: "赵淑媛，广州大学统计学本科生，关注统计推断、数据建模与机器人控制。"
author_profile: true
lang: zh-CN
---

<section class="profile-section" markdown="1" aria-labelledby="个人简介">

# 个人简介 {#个人简介}

我是**广州大学统计学本科生赵淑媛**，预计2027年7月毕业。我参与未知背景下的 Poisson 精确推断研究，也在竞赛中探索了纵向健康数据分析与可持续旅游建模。我关注数学与计算方法如何应用于真实问题。

在机器人控制实习中，我参与了六轴机械臂的**导纳与阻抗控制**开发，开展 MuJoCo 仿真与 ELFIN10-L 真机联调。我已收到**香港科技大学（广州）Redbird MPhil** 的录取 offer，预计2027年9月入学。

[英文简历 PDF]({{ '/files/Zhao_Shuyuan_CV.pdf' | relative_url }}) · [English]({{ '/' | relative_url }})

</section>

<section class="profile-section" markdown="1" aria-labelledby="教育背景">

# 教育背景 {#教育背景}

<div class="education-list" markdown="0">
<div class="education-entry">
<a class="education-logo" href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="访问香港科技大学广州官网">
<img src="{{ '/images/universities/hkust-gz-logo.png' | relative_url }}" alt="香港科技大学广州标识" width="46" height="46" loading="lazy">
</a>
<div class="education-details">
<h3 class="education-school"><a href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer">香港科技大学（广州）<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
<p class="education-degree">Redbird MPhil</p>
<p class="education-note">已确认收到 offer</p>
</div>
<p class="education-dates">2027年9月—2029年7月<br><span>预计</span></p>
</div>
<div class="education-entry">
<a class="education-logo" href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="访问广州大学官网">
<img src="{{ '/images/universities/gzhu-mark.png' | relative_url }}" alt="广州大学校徽" width="46" height="46" loading="lazy">
</a>
<div class="education-details">
<h3 class="education-school"><a href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer">广州大学<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
<p class="education-degree">统计学本科</p>
</div>
<p class="education-dates">2023年9月—2027年7月<br><span>预计毕业</span></p>
</div>
</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="论文">

# 论文 {#论文}

<div class="profile-entry publication-entry" markdown="1">

**Dynamic truncation and the Berger–Boos corrected h–function method for optimal exact Poisson confidence intervals with unknown backgrounds**<br>
Lu, H., **Zhao, S.**, & Wu, Q.<br>
*已投稿至 [Statistical Papers](https://link.springer.com/journal/362)。*

针对弱信号与未知背景下的稀有事件数据开展精确 Poisson 推断研究，结合动态截断、Berger–Boos 校正与 h-function，比较区间覆盖率和效率，并应用于 KARMEN 中微子探测数据。

</div>

<div class="profile-entry publication-entry" markdown="1">

**[基于 DPSIR 和非线性规划的可持续旅游模型——以美国阿拉斯加州朱诺市为例](https://doi.org/10.61369/ASDS.12187)**<br>
王嘉蔚，**赵淑媛**，顾子林。<br>
*Applied Statistics and Data Science（ASDS），2025 年，1(3)：112–116。*

结合熵权 TOPSIS、DPSIR 框架与非线性规划，并采用遗传算法求解，分析朱诺市旅游收益、资源约束与居民利益之间的权衡。

[DOI](https://doi.org/10.61369/ASDS.12187) · [论文 PDF]({{ '/files/publications/sustainable-tourism-dpsir-2025.pdf' | relative_url }})

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="研究经历">

# 研究经历 {#研究经历}

<div class="profile-entry" markdown="1">

### 未知背景下的 Poisson 精确推断
<p class="entry-meta"><em>研究成员 · 2025年9月至2026年4月</em></p>

- 研究弱信号与未知背景条件下的稀有事件推断，应用背景包括高能物理与生物医学检测。
- 参与结合 Poisson 分位数、Berger–Boos 校正与 h-function 的动态截断方法研究。
- 通过仿真实验，对比 Bayesian、IM、NIM 方法下初始、一次改进和最优精确置信区间的覆盖率与效率。

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="实习经历">

# 实习经历 {#实习经历}

### 东莞市新佰人机器人科技有限责任公司 — 控制算法部门
<p class="entry-meta"><em>强化学习助理工程师实习 · 2026年6月至9月</em></p>

<div class="internship-project" markdown="1">

#### 六轴机械臂笛卡尔空间导纳控制

- 建立质量—阻尼—刚度导纳模型，在 MuJoCo 中验证三维受力响应，并修正姿态表示不一致引起的坐标变换与响应方向问题。
- 参与 CODESYS 定点导纳部署及直线轨迹增量叠加，采用分段插补缓解导纳响应滞后，修正 ACS/MCS 坐标系配置问题。
- 开展 Python–CODESYS TCP 通信与 ELFIN10-L 真机联调，处理传感器零点偏置、采样周期和目标指令更新频率问题，并定位传感器数据停止刷新故障。

</div>

<div class="internship-project" markdown="1">

#### 六轴机械臂关节空间阻抗控制

- 基于关节位置与速度误差建立弹簧—阻尼阻抗控制，参与六轴阻抗控制实现与真机 CST 力矩输出测试。
- 联调 Pinocchio 重力补偿与摩擦补偿，校准驱动力矩映射及量级，调整力矩限幅并加入通信失联保护。
- 修正 ELFIN10-L 正运动学模型，通过正逆运动学回环与新旧插补器并行对照验证，开展直线轨迹与斜面接触测试。

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="竞赛经历">

# 竞赛经历 {#竞赛经历}

<div class="profile-entry competition-entry" markdown="1">

### 中老年人健康风险的多维量化与纵向分析
**2025年（第十一届）全国大学生统计建模大赛｜广东赛区一等奖**

<p class="entry-meta"><em>项目负责人 · 2025年3月至5月</em></p>

- 负责选题、研究框架、建模策略与团队协调，围绕中老年人健康风险开展纵向分析。
- 基于 CHARLS 三期共21,000余条纵向记录，构建6,800余个建模样本，结合随机森林、XGBoost 特征筛选，以及固定效应和 GEE 模型开展分析。
- 从26项指标中识别12项关键衰弱预测因素，形成涵盖心理健康、身体活动、经济条件、认知功能与医疗服务的五维风险框架，并分析年龄差异，为分层干预与社区健康规划提供建议。

</div>

<div class="profile-entry competition-entry" markdown="1">

### 可持续旅游优化建模
**2025年美国大学生数学建模竞赛（Mathematical Contest in Modeling，MCM）｜Honorable Mention**

<p class="entry-meta"><em>团队成员，负责报告写作与建模分析 · 2025年1月</em></p>

- 整合文献与多源数据，参与 DPSIR 指标体系与非线性优化分析，研究朱诺市旅游收益、生态约束、基础设施与居民利益之间的权衡。
- 组织报告结构、可视化遗传算法结果，并开展朱诺市与西安的对比分析。

</div>

<div class="profile-entry competition-entry" markdown="1">

### 高熵合金性能预测与优化平台商业化方案
**中国国际大学生创新大赛（2025）广东省分赛｜银奖**

<p class="entry-meta"><em>技术商业化与商业计划负责人 · 2025年4月至8月</em></p>

- 将机器学习辅助高熵合金性能预测与优化平台的技术内容，转化为面向航空航天与高端制造的产品方案。
- 开展市场分析，协调技术、营销、财务与法律信息，形成商业化策略与商业计划书。

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="荣誉奖项">

# 荣誉奖项 {#荣誉奖项}

- **2025年** — 第十一届全国大学生统计建模大赛，广东赛区一等奖。
- **2025年** — 美国大学生数学建模竞赛（Mathematical Contest in Modeling，MCM），Honorable Mention。
- **2025年** — 中国国际大学生创新大赛（2025）广东省分赛，银奖。
- **2025年** — “正大杯”第十五届全国大学生市场调查与分析大赛，国家三等奖。
- 广州大学一等奖学金。

</section>

<section class="profile-section" markdown="1" aria-labelledby="技术能力">

# 技术能力 {#技术能力}

- **编程与工具：** Python、R、Linux、Git、CODESYS。
- **统计与数据分析：** 统计建模、纵向数据分析、机器学习、问卷数据分析，NumPy、Pandas、Matplotlib。
- **机器人技术：** MuJoCo、Pinocchio、导纳控制、阻抗控制、PD/PID 与动力学补偿。
- **语言：** 普通话母语，英语 IELTS 6.5。

</section>
