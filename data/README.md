# 数据目录说明

**本目录中的数据不会上传到 GitHub**（已被 `.gitignore` 排除）。请勿手动强制添加数据文件。

## 数据集获取方式

### B：PhysioNet/CinC 2016 心音分类挑战赛数据

- 页面：https://physionet.org/content/challenge-2016/1.0.0/
- 公开数据，可直接下载。

### C：CirCor DigiScope 2022

- 页面：https://physionet.org/content/circor-heart-sound/1.0.3/
- 需要注册 PhysioNet 账号并签署数据使用协议（DUA）后下载。

### A：NHS 临床试验数据（导师提供）

- 格拉斯哥 QEUH 自测数据（光学听诊器，约 36 名受试者），导师通过网盘分发。
- **仅限课题组内本地使用，严禁上传至任何公开平台（包括本仓库）。**

## 本地目录约定

```
data/
├── raw/        # 原始下载的数据，不改动
│   ├── cinc2016/
│   ├── circor2022/
│   └── nhs/
└── processed/  # 预处理后的分段与增强样本
```
