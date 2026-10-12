<div align="center">

<img src="assets/ncu-wordmark.png" alt="南昌大学 Nanchang University" width="360">

</div>

<div align="center">

# 人机协同（Human–AI Collaboration）课程实验作品集

**南昌大学 · 全学期 16 周实验记录主仓库**

</div>

<div align="center">

 **GitHub 仓库**：https://github.com/0712yu/NCU-human-AI ｜ 状态：公开

</div>

---

## 一、个人信息

| 项目 | 内容 |
| :--- | :--- |
| 学校 | 南昌大学（Nanchang University） |
| 学号 | **7902126151** |
| 姓名 | **叶雨婷** |
| 专业 | 食品科学与工程 |
| 课程方向 | 人机协同 / AI 通识与实操 |

## 二、这个仓库是做什么用的？

用一句大白话说：**这是我整个学期的“云端实验笔记本 + 作品陈列柜”。**

- 每周的实验报告、代码、数据、图片，都会放进对应星期的文件夹里，一星期一个“抽屉”；
- 每次改动都会通过 Git 形成一个**存档点（Commit）**，就像游戏里的“存档”，改错了可以随时读档回到过去；
- 仓库托管在 GitHub 云端，不怕电脑丢失，随时随地都能查看、提交作业、向老师和同学展示成果。

## 三、全学期 16 周实验目录树

> 以下为学期规划结构，随课程推进逐步填充实验内容。

```text
NCU-human-AI/
├── .gitignore                          # Git 忽略清单（缓存/密钥等不上传）
├── README.md                           # 仓库说明（本文件）
├── assets/                             # 公共图片资源
│   ├── ncu-wordmark.png                # 南昌大学校名标识（来源于官网）
│   └── ncu-emblem.png                  # 南昌大学校徽（来源于官网）
├── week01-课程导论与协作环境搭建/
│   └── README.md                       # 第 1 周实验报告
├── week02-提示词工程基础/
│   └── README.md
├── week03-AI辅助信息检索与文献调研/
│   └── README.md
├── week04-AI辅助学术写作与润色/
│   └── README.md
├── week05-AI辅助数据处理与分析/
│   └── README.md
├── week06-AI辅助数据可视化/
│   └── README.md
├── week07-AI图像生成与视觉设计/
│   └── README.md
├── week08-AI辅助知识管理与笔记/
│   └── README.md
├── week09-人机协作头脑风暴与创意方法/
│   └── README.md
├── week10-AI辅助编程与任务自动化/
│   └── README.md
├── week11-AI伦理学术诚信与安全/
│   └── README.md
├── week12-AI在食品科学中的应用（一）/
│   └── README.md
├── week13-AI在食品科学中的应用（二）/
│   └── README.md
├── week14-课程综合项目人机协作实战/
│   └── README.md
├── week15-项目迭代与展示准备/
│   └── README.md
└── week16-期末成果展示与课程复盘/
    └── README.md
```

## 四、每周实验提交规范

1. 当周材料一律放入对应的 `weekXX-主题/` 文件夹，命名规范、不随意堆放；
2. 实验报告写在当周目录的 `README.md` 中，建议按「实验目标 → 内容与过程 → 结果与产出 → 问题与反思」四段式撰写；
3. 大文件、API 密钥、系统缓存不要提交（`.gitignore` 已自动拦截常见类型）；
4. 每次做完实验，在仓库根目录终端执行“提交三步曲”：

```bash
git add .                                    # 1. 把改动放进“待提交区”
git commit -m "weekXX: 本周实验小结"          # 2. 生成一个存档点
git push                                     # 3. 同步到 GitHub 云端
```

## 五、Git 常用命令小抄

| 命令 | 大白话解释 |
| :--- | :--- |
| `git status` | 看看现在有哪些文件改动还没处理 |
| `git add .` | 把所有改动装进“快递箱”（暂存区） |
| `git commit -m "说明"` | 封箱并贴标签，生成一个存档点 |
| `git push` | 把本地存档快递到 GitHub 云端 |
| `git pull` | 把云端最新存档下载回本地 |
| `git log --oneline` | 查看历史存档清单 |

## 六、说明

- 校名标识与校徽图片均来源于南昌大学官方网站（ncu.edu.cn），仅供本课程学习交流使用；
- 本仓库为课程个人作品集，内容遵循学术诚信规范，AI 辅助产出已在各周报告中注明。

---

<div align="center">

<img src="assets/ncu-emblem.png" alt="南昌大学校徽" width="72">

**格物致新 · 厚德泽人**

</div>
