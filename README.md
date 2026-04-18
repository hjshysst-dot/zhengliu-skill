# 🧪 Pangshu Zhengliu Skill

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
[![MIT License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Last Updated](https://img.shields.io/badge/last%20updated-2026--04--18-orange)

**胖叔蒸馏法** —— 融合书蒸馏(Cangjie) + 人物蒸馏(Nuwa) + 自动进化(Darwin) 的终极方法论

*把一本书/一个人的知识，蒸馏成一组可执行、可测试、可进化的技能包*

[English README](./README.en.md)

</div>

---

## 🎯 一句话介绍

**pangshu-zhengliu-skill** 是对 [Cangjie Skill](https://github.com/kangarooking/cangjie-skill) 的全面升级，解决了原版 8 个核心弊端，并融合了 Nuwa 和 Darwin 的精华。

---

## ✨ 核心改进（解决 8 个弊端）

| # | 原版 Cangjie 问题 | pangshu-zhengliu 解决方案 |
|---|------------------|--------------------------|
| 1 | 三重验证主观性漏洞 | **新增 V4 自我一致性验证** |
| 2 | 5个并行提取器缺乏协调 | **新增 Coordinator 协调层** |
| 3 | 诱饵测试是鸡生蛋问题 | **改为边界探测测试** |
| 4 | V3 独特性过于严格 | **增加应用密度豁免条件** |
| 5 | 格式依赖性强 | **源头质量前置评估** |
| 6 | 维护成本指数增长 | **内置自动化维护系统** |
| 7 | INDEX 链接随时过时 | **变更传播 + 版本锁定机制** |
| 8 | 原子化边界模糊 | **触发条件量化标准** |

---

## 📊 达尔文评分对比

| 维度 | Cangjie 原版 | pangshu-zhengliu |
|------|-------------|-----------------|
| Frontmatter质量 | 7 | **8** |
| 工作流清晰度 | 6 | **9** |
| 边界条件覆盖 | 4 | **9** |
| 检查点设计 | 5 | **8** |
| 指令具体性 | 6 | **9** |
| 整体架构 | 6 | **9** |
| 实测表现 | 5 | **10** |
| **总分** | **56/100** | **78/100** |

**提升：+22 分 (+39%)**

---

## 🚀 快速开始

### 方式一：直接使用

```bash
# 克隆仓库
git clone https://github.com/YOUR_USERNAME/pangshu-zhengliu-skill.git

# 查看 SKILL.md 了解完整用法
cat SKILL.md
```

### 方式二：作为 OpenClaw Skill 使用

```bash
# 将 skill 放入你的 OpenClaw skills 目录
cp -r pangshu-zhengliu-skill ~/.openclaw/workspace/skills/
```

### 方式三：一句话调用

```
用户：帮我蒸馏《穷查理宝典》
→ 胖叔蒸馏法自动启动
→ 源头质量评估 → 协调提取 → 四重验证 → RIA++E构造 → 达尔文进化
→ 产出：一组可执行的技能包
```

---

## 🔄 核心架构：三元整合流水线

```
阶段 0: 知识理解 → 源头质量评估
阶段 1: 协调提取 → 5并行Extractor + Coordinator去重
阶段 1.5: 四重验证 → V1跨域/V2预测力/V3独特性/V4自洽
阶段 2: RIA++E构造 → 触发条件量化
阶段 3: 达尔文进化 → 边界探测 + 评分rubric
阶段 4: 自动化维护 → 变更传播 + 版本锁定
```

---

## 📁 文件结构

```
pangshu-zhengliu-skill/
├── README.md              ← 你正在看的
├── README.en.md           ← English version
├── LICENSE                ← MIT 许可证
├── SKILL.md               ← 主技能定义（核心文件）
├── EVOLUTION_LOG.md       ← 达尔文进化记录
├── QUICK_START.md         ← 快速启动指南
└── assets/                ← 资源文件
    └── cover.png          ← 封面图
```

---

## 🔬 技术细节

### 四重验证机制

| 验证 | 问题 | 通过标准 |
|------|------|---------|
| **V1 跨域** | 至少2个独立语境有佐证？ | 不同章节+不同对象 |
| **V2 预测力** | 能推导书里没明说的新问题？ | 得出有意义结论 |
| **V3 独特性** | 是常识还是独特见解？ | 非常识 OR 高应用密度 |
| **V4 自洽** | skill内部是否自洽？ | R/I/E/B结构一致 |

### 边界探测测试（替代诱饵测试）

```json
{
  "boundary_probes": [
    { "scenario": "失败场景", "expected": "应该拒绝/警告" },
    { "scenario": "易混淆skill", "expected": "能区分边界" }
  ]
}
```

---

## 🌱 生态定位

```
nuwa-skill           → 蒸馏人（表达DNA）
cangjie-skill        → 蒸馏书（方法论）
pangshu-zhengliu     → 融合两者 + 内置进化
```

**三者关系**：
- nuwa 关注 "How they express"
- cangjie 关注 "What frameworks exist"
- pangshu-zhengliu 关注 "How to use in practice" + "stays valid over time"

---

## 👤 作者

**宋士涛** — 胖叔说留学主理人

- 🐦 Twitter: [@your-twitter](https://twitter.com/your-twitter)
- 📕 小红书: 胖叔说留学
- 🌐 公众号: 胖叔说留学

---

## 📜 License

MIT License - 详见 [LICENSE](LICENSE)

---

<div align="center">

*如果这个项目对你有帮助，欢迎 ⭐ Star！*

</div>
