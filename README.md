<div align="center">

# 润学导航 · Claude Edition
### Run Abroad Pathfinder

**填写少量基本信息，看清自己能走哪些出国路径 —— 以及还差什么。**

收录 72 条全球签证与移民路径 · Anthropic Claude 风格全新重构 · 纯本地无后端计算

[![License: MIT](https://img.shields.io/badge/License-MIT-C96442.svg)](LICENSE)
[![No Dependencies](https://img.shields.io/badge/dependencies-0-2D6A4F.svg)](#-项目结构)
[![Pathways](https://img.shields.io/badge/收录路径-72-B5791E.svg)](js/data.js)
[![Style: Claude](https://img.shields.io/badge/UI-Claude%20Parchment-C96442.svg)](css/style.css)
[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-在线推演-2D6A4F?style=flat&logo=github)](https://stanlll-cloud.github.io/run-abroad/)

<br>

## [👉 点击进入在线推演 👈](https://stanlll-cloud.github.io/run-abroad/)

<br>

[快速开始](#-快速开始) · [Claude 视觉系统](#-claude-风格全新重构) · [贡献数据](CONTRIBUTING.md) · [免责声明](#️-免责声明)

</div>

---

## 🎨 Claude 风格全新重构

本项目基于开源的出国路径规则库，采用 **Anthropic Claude** 标志性设计哲学进行全局视觉与交互重塑：

- **暖象牙纸底 (Warm Parchment `#FAF9F5`)**：告别刺眼白屏与冰冷数码感，采用 Claude 标志性的温润书卷质感与深炭文字排版。
- **Claude 陶土珊瑚主色 (`#C96442`)**：点睛以温暖而克制的 Terracotta 珊瑚红，搭配温润柔光微交互。
- **人文典雅衬线标题**：Hero 与各大章节采用高品质衬线排版，兼具智性美感与阅读舒适度。
- **状态卡片层级重构**：
  - 🟢 **符合条件**：Claude 沉稳森林绿 (`#2D6A4F` / `#EDF6F1`)
  - 🟡 **差一点即可**：Claude 蜂蜜琥珀黄 (`#B5791E` / `#FDF7EC`)
  - 🟠 **需长期规划**：Claude 陶土珊瑚红 (`#C96442` / `#FBF3EE`)
  - ⚪ **暂时走不通**：Claude 静谧石灰岩 (`#7A7670` / `#F2EFEA`)
- **全端自适应深色模式**：深度适配系统 Dark Mode，采用温润的 Espresso 深棕黑底（非生硬蓝黑），夜间使用同样舒适。

---

## 为什么做这个

想出国的人，通常最先遇到的不是「哪个国家好」，而是一个更基础的问题：

> **以我现在的条件，到底有哪些路是真的走得通的？**

网上不缺移民信息，缺的是**针对你个人情况的筛选**。你会看到几十篇「XX 国签证全解析」，每一篇都在讲政策条文，但没有一篇会告诉你：你 31 岁、双非本科、雅思 6.0、工作 6 年——**这些条件下，哪条路现在就能走，哪条路差一点，哪条路已经彻底关上了。**

于是你在几十个标签页之间反复比对，一周后仍然不知道下周该做什么。

这个项目就是来解决这一步的。它不是又一份签证清单，而是一个**决策工具**：把你的条件和 72 条路径的门槛逐项比对，输出一份排过序的、标注了具体缺口的结果。

---

## 它和其他移民信息站的区别

<table>
<tr>
<td width="50%" valign="top">

**常见的移民信息站**

- 按国家罗列签证政策
- 你需要自己对照条件
- 只告诉你「要求是什么」
- 符合 / 不符合的二元判断
- 看完仍然不知道先做什么

</td>
<td width="50%" valign="top">

**润学导航 (Claude Edition)**

- 按你的条件筛选并实时排序
- 引擎自动逐项精准比对
- 明确告诉你「你还差什么」
- 四档分类，覆盖中间过渡地带
- 直接给出优先级建议与官方直链

</td>
</tr>
</table>

### 三个核心设计

#### 1️⃣ 不做二元判断

现实中很少有人是「完全符合」或「完全不符合」。大部分人都卡在中间，所以结果分成四档：

| 分档 | 含义 |
|:---|:---|
| ✅ **符合条件** | 所列硬性门槛你都过了，可以直接去研究申请材料 |
| 🟡 **差一点** | 只差一两项，且都是能补上的（语言、经验、资金、offer） |
| 🟠 **需要长期准备** | 缺口较多，但方向上并没有被堵死 |
| ⚪ **暂时走不通** | 存在短期无法改变的硬门槛 |

#### 2️⃣ 区分硬门槛与软门槛

- **硬门槛（改不了的）**：年龄超了、学历不够、不是特定院校、毕业年限过了。只要踩中一个，这条路就归入「暂时走不通」。
- **软门槛（可以补的）**：雅思差 0.5、工作经验差一年、存款还差一点、还没有 offer。这些会明确标在卡片上，告诉你**只要补上这一项，这条路就能走**。

#### 3️⃣ 告诉你代价和时间

结果卡片不仅告诉你「差什么」，还给出粗略的**时间与精力预估**：

> 预计准备 3–6 个月 · 花费：低 · 英语需提升至 雅思 6.5

让你在挑路的时候能权衡：是花半年考个语言更现实，还是攒两年工作经验更稳妥。

---

## 🗺️ 收录的路径类型

<table>
<tr><th width="30%">类型</th><th>包含的代表性路径</th></tr>
<tr><td>🌏 <b>打工度假</b></td><td>澳大利亚 WHV · 新西兰 WHV</td></tr>
<tr><td>🎯 <b>找工作签</b></td><td>德国机会卡 · 奥地利找工作签 · 瑞典高学历找工作签 · 荷兰求职年（Orientation Year）· 葡萄牙求职签</td></tr>
<tr><td>💼 <b>工作签证（需雇主）</b></td><td>日本技术·人文·国际业务 · 德国 EU 蓝卡 · 英国 Skilled Worker · 爱尔兰 Critical Skills · 新西兰 AEWV · 新加坡 EP · 智利工签</td></tr>
<tr><td>🏆 <b>人才引进</b></td><td>香港高才通 A/B/C 类 · 英国全球人才（Global Talent）· 澳大利亚全球人才 GTS · 迪拜黄金签证</td></tr>
<tr><td>📊 <b>技术移民</b></td><td>加拿大快速通道 Express Entry（常规轮 / 紧缺职业 / 法语定向）· 澳大利亚 189 / 190 / 491 · 新西兰 SMC</td></tr>
<tr><td>📚 <b>留学 & 毕业工签</b></td><td>英国 PSW · 香港 IANG · <b>加拿大 PGWP</b> · 新西兰 PSW · 爱尔兰 Stamp 1G · 德国 / 意大利公立留学 · 日本 / 爱尔兰语言学校 · 欧盟 Erasmus Mundus 全奖</td></tr>
<tr><td>💻 <b>数字游民</b></td><td>葡萄牙 D8 · 西班牙 DNV · 泰国 DTV · 马来西亚 DE Rantau · 挪威自雇 · 克罗地亚 · 斯洛文尼亚</td></tr>
<tr><td>🚀 <b>创业投资</b></td><td>加拿大 SUV · 英国创新创始人 · 阿联酋黄金签证 · 日本经营管理 · 美国 EB-5</td></tr>
<tr><td>🔨 <b>职业教育</b></td><td>德国双元制 Ausbildung · <b>日本特定技能</b> · <b>加拿大魁北克 PEQ</b> · 芬兰职业教育 VET</td></tr>
<tr><td>🌾 <b>季节性工作</b></td><td>欧盟季节工许可 · 新西兰季节性工作签证（免英语）</td></tr>
<tr><td>🛬 <b>低成本落脚</b></td><td>格鲁吉亚免签 1 年 · 乌拉圭自主经济能力居留 · 厄瓜多尔存款居留 · 波兰低成本留学</td></tr>
</table>

覆盖 **32 个国家 / 地区**，每条路径都附有政府官网链接。

---

## 🚀 快速开始

纯静态单页架构，没有构建步骤，没有 npm，没有任何第三方打包依赖。克隆下来直接打开：

```bash
git clone https://github.com/stanlll-cloud/run-abroad.git
cd run-abroad

open index.html              # macOS 直接打开
python3 -m http.server 8000  # 或起个本地轻量服务器访问 http://localhost:8000
```

### 部署到 GitHub Pages

仓库已内置完整的 GitHub Actions 持续集成与部署工作流 (`.github/workflows/pages.yml`)：

1. 打开仓库 **Settings → Pages**
2. 在 **Build and deployment → Source** 中选择 `GitHub Actions`
3. 推送到 `main` 分支即可自动构建并发布到 GitHub Pages

---

## 🧩 项目结构

```
run-abroad/
├── index.html          全球路径主筛选（72 条完整路径计算）
├── nomad.html          数字游民专题（月收入门槛横向对比）
├── hk.html             香港工作签证专题（高才通 / IANG / 专才决策树）
├── student.html        大学生专题（14 条在读与应届低成本路径）
├── wild.html           野路子专题（无情道 / 扎根居留等边缘风险深度拆解）
├── pathway.html        全球路径深度详情页
├── student-pathway.html 大学生路径深度指南与分阶段攻略
├── css/
│   └── style.css       Anthropic Claude 风格设计系统（无外部依赖）
├── js/
│   ├── data.js         72 条签证路径的结构化门槛与官方信源
│   ├── engine.js       初筛匹配引擎、硬门槛判断与缺口估算
│   ├── app.js          表单交互、自绘 Select、URL 状态持久化
│   ├── detail.js       路径详情页渲染
│   ├── nomad.js        数字游民对比逻辑
│   ├── hk-data.js      香港签证数据
│   ├── hk.js           香港签证交互
│   ├── student-data.js 大学生路径数据
│   ├── student-guides.js 大学生攻略长文本
│   └── student.js      大学生页面逻辑
└── CONTRIBUTING.md     数据贡献与纠错规范
```

---

## 🔒 隐私与安全性

- **100% 浏览器本地运算**：没有后端 API，没有数据库，不记录任何用户信息。
- **无追踪脚本**：不引入任何第三方 Google Analytics、广告或 Cookie 收集。
- **安全分享**：唯一的持久化是「复制结果链接」功能——它将你的选项通过 Base64 编码在 URL hash 中，完全由你自主决定是否分享给他人。

---

## ⚠️ 免责声明

**这是初筛与认知工具，不是法律意见。**

- 结果只说明「根据公开规则，值得先查哪几条路」，**不代表你一定能申请成功**。真实签证涉及材料、资金流向、背景审查等复杂人工判断。
- **政策变动极快。** 门槛与配额随时调整，每张卡片底部均配有移民局官方网站链接，**最终务必以官方最新法案为准**。
- **防范中介套路。** 本项目绝大多数路径均支持个人 DIY 线上递交，任何承诺「保过」「内部通道」的均需警惕。

---

## 👏 致谢与溯源

本项目规则数据与结构模型参考开源项目 [RadishXN/run-abroad](https://github.com/RadishXN/run-abroad)，在此对原项目作者及开源社区贡献者表达诚挚感谢。

---

<div align="center">

**MIT License** · 开放共享 · 愿每位勇敢者找到属于自己的广阔天地

</div>
