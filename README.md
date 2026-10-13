# 南昌大学 · 本学期课程个人作品集

![南昌大学](https://img.shields.io/badge/%E5%8D%97%E6%98%8C%E5%A4%A7%E5%AD%A6-Nanchang%20University-red?style=flat-square)
![公开仓库](https://img.shields.io/badge/visibility-public-brightgreen?style=flat-square)
![维护中](https://img.shields.io/badge/status-active-success?style=flat-square)

> 本仓库用于系统化保存本学期（16 周）所有课程实验、作业、报告与项目代码，
> 既是学习轨迹的"云端备份"，也是求职/保研时最直观的"作品集"。

---

## 👤 个人信息

| 项目 | 内容 |
| --- | --- |
| 学校 | 南昌大学（Nanchang University） |
| 学号 | `STUDENT_ID`（请自行替换为真实学号） |
| 姓名 | `YOUR_NAME`（请自行替换为真实姓名） |
| 专业 | `YOUR_MAJOR`（请自行替换为真实专业） |
| 仓库地址 | <https://github.com/cwb385/cwb385.github.io> |

> ⚠️ 首次使用本仓库，请用 **VSCode → Ctrl+Shift+H** 全局搜索
> `STUDENT_ID` / `YOUR_NAME` / `YOUR_MAJOR` 替换为真实信息（仓库地址已自动填好）。

---

## 📚 16 周实验目录树

每周一个独立文件夹，按"周次-课程-主题"命名，文件夹内统一结构：

```
week-XX-课程简称-主题/
├── README.md       # 实验目的 / 步骤 / 心得（必填）
├── src/            # 源代码
├── docs/           # 报告 / 截图 / 附件
└── notes.md        # 课堂笔记（可选）
```

### 目录全景

```text
.
├── week-01-课程-主题/      # 第 1 周
├── week-02-课程-主题/      # 第 2 周
├── week-03-课程-主题/
├── week-04-课程-主题/
├── week-05-课程-主题/
├── week-06-课程-主题/
├── week-07-课程-主题/
├── week-08-课程-主题/      # 学期中段（通常安排期中检查）
├── week-09-课程-主题/
├── week-10-课程-主题/
├── week-11-课程-主题/
├── week-12-课程-主题/
├── week-13-课程-主题/
├── week-14-课程-主题/
├── week-15-课程-主题/      # 期末项目启动
├── week-16-课程-主题/      # 期末收尾 / 答辩
├── .gitignore             # Git 忽略规则（系统垃圾、编译产物等）
├── LICENSE                # 许可证（MIT / Apache-2.0 二选一）
└── README.md              # 你正在看的这个文件
```

> 💡 **小贴士**：每周末花 10 分钟 `git add .` → `git commit -m "weekXX: 提交说明"` → `git push`，
> 16 周后回头看，你会感谢今天努力的自己。

---

## 🚀 快速开始

### 第一次使用

```bash
# 克隆仓库到本地
git clone https://github.com/cwb385/cwb385.github.io.git
cd cwb385.github.io

# 替换占位符（VSCode 全局替换更快）
#   STUDENT_ID  -> 你的学号
#   YOUR_NAME   -> 你的姓名
#   YOUR_MAJOR  -> 你的专业
```

### 每周提交流程

```bash
git pull                         # 拉取最新
git add .                        # 暂存本周修改
git commit -m "week-XX: 简要描述"  # 写提交说明
git push                         # 推到 GitHub
```

---

## 🧰 推荐工具

| 工具 | 用途 | 链接 |
| --- | --- | --- |
| VS Code | 代码编辑 | <https://code.visualstudio.com/> |
| GitHub Desktop | 图形化 Git（可选） | <https://desktop.github.com/> |
| Obsidian / Typora | 写 Markdown 笔记 | — |

---

## 📜 许可证

本作品集采用 **MIT License** —— 你可以自由引用、修改、再发布，保留原作者署名即可。
详见 [LICENSE](./LICENSE) 文件。

---

## 🙏 致谢

感谢南昌大学提供的学习平台与资源；
感谢结对工程顾问在 Git/GitHub 工作流上的悉心指导。

> *"千里之行，始于足下。"* —— 老子
