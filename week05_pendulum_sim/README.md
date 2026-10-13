# 第五周实验 · 单摆模拟（Pendulum Simulation）

> 专业：**护理** · 学号：**666** · 姓名：**小狗**

| 项目 | 内容 |
| :--- | :--- |
| 实验者 | 小狗（学号 666）|
| 实验周次 | Week 05（第 5 周）|
| 实验方向 | 单摆运动模拟 (Pendulum Simulation) |
| 子模块路径 | `week05_pendulum_sim/` |
| 工作区状态 | 🧪 **无菌（Sterile Baseline）** — 仅本 README，无任何遗留代码或脏数据 |
| 父仓库基线 | `6c7b460`（本次工作区从该 commit 起步）|

---

## 🧫 关于"无菌工作区"

"无菌"是生物 / 化学实验里的概念，借用在这里表示：

- 本目录**与周记目录 `week-05/` 并列、互不污染**，是专门留给你做单摆实验的隔离空间。
- 除本 `README.md` 外，目录**不预装**任何代码、虚拟环境、示例数据、IDE 配置或随机文件。
- 后续实验代码、报告、图表、数据集在落地之前，请检查 `.gitignore` 是否会误伤（例如暂时屏蔽 `__pycache__/`、`.venv/` 等）。
- 一旦有任何改动，`git status` 都能立刻看见，**不会有"幽灵文件"潜伏在你看不见的地方**。

---

## 📐 建议的文件组织

```
week05_pendulum_sim/
├── README.md         ← 本文件
├── src/              ← 模拟源代码
│   ├── pendulum.py
│   └── integrate.py
├── data/             ← 实验原始数据 / CSV
├── figures/          ← 生成的图像
├── docs/             ← 实验报告（Markdown / PDF）
└── notebooks/        ← Jupyter Notebook 草稿
```

> 若你不需要其中某些子目录，直接不创建即可——"无菌"的精髓是**只把必要的东西搬进来**。

---

## 🧪 实验计划（占位）

- [ ] 选模拟方法（数值积分 / 解析法 / SymPy 推导）
- [ ] 搭建参数化物理模型（摆长 L、初摆角 θ₀、重力 g、阻尼系数）
- [ ] 与小角度近似结果对比，验证误差边界
- [ ] 撰写实验报告并提交至 `docs/`
- [ ] 在 `week-05/README.md` 中回链本工作区

---

## 🔁 与父仓库的协作

```bash
# 1. 确认基线与父仓库一致
cd /d/新建文件夹
git log --oneline -n 1      # 期望: 6c7b460

# 2. 在本目录内开发
cd week05_pendulum_sim/

# 3. 完成阶段性工作后锁定基线
git add .
git commit -m "feat(week05): <本次进展描述>"
git push
```

---

## 📜 基线与变更记录

| 事件 | Commit | 说明 |
| :--- | :--- | :--- |
| 🧪 无菌初始化 | 见父仓库 `git log` 中第二条 | 创建 `week05_pendulum_sim/`，仅含本 README |
| 父仓库基线 | `6c7b460` | `chore: initialize Nanchang University portfolio repository` |

> 创建时间：见 git 提交时间戳 · 维护者：小狗 @ 南昌大学
