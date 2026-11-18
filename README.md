# 赵善远 · Zhao Shanyuan

人工智能本科应届（2026 届），关注 **大模型应用落地** 与 **AI 质量工程**。
做过深度学习模型的训练与评测，也习惯把模型包装成能真正跑起来的产品。

---

## 我在做什么

- **非侵入式负荷监测（NILM）**：在 UK-DALE House 1 上复现并对比 Seq2Point / CNN / WaveNet / BGRU 等多类负荷分解模型，把 WaveNet 调整为 8 层膨胀卷积（接收野 511 步），并独立完成一套全栈可视化分析平台
- **AI 质量工程**：关注用视觉模型做 UI 缺陷检测（图标错位、文字截断）、用大模型批量生成与评估测试用例、对缺陷单做自动分类去重
- **引擎与图形**：业余用 UE5 + C++ 写游戏 Demo，对实时渲染和底层实现细节有兴趣

## 代表项目

| 项目 | 说明 | 技术栈 |
| --- | --- | --- |
| [nilm-seq2point-models](https://github.com/ningDay/nilm-seq2point-models) | 多类负荷分解模型在 UK-DALE 上的复现与对比实验。改一个配置项即可切换模型与目标电器，跑通「数据生成 → 训练 → 推理 → 反归一化 → 指标统计」全流程，附论文实测 MAE / SAE 对比表 | PyTorch · NumPy · HDF5 · Jupyter |
| [nilm-visual-platform](https://github.com/ningDay/nilm-visual-platform) | 负荷分解可视化平台。选模型与电器即可秒级分解家庭总功率，输出预测/真实/聚合三线对比、回归与分类指标、分功率区间误差分析，支持自定义 CSV 上传与结果导出 | FastAPI · PyTorch · React · TypeScript · Recharts |

> 两个仓库是同一份毕业设计的两半：前者回答「模型训得好不好」，后者回答「结果看得懂看不懂」。

## 技术栈

- **语言**：Python、C++、TypeScript、SQL
- **深度学习**：PyTorch（自定义模型 / 训练循环 / 指标实现）、NumPy、模型评测与误差分析
- **后端**：FastAPI、RESTful API、Linux、Git
- **前端**：React、TypeScript、Tailwind CSS、Recharts
- **引擎**：Unreal Engine 5（C++）

## 经历

- **中国石油大学（北京）** · 人工智能 · 本科 · 2020.09 – 2026.06
  毕业设计：基于深度学习的非侵入式负荷分解与可视化平台
- **北京扶摇动力** · UE 仿真工程师 · 2026.01 – 2026.07
- **中国石油研究院** · 算法测试实习 · 2023.06 – 2023.09

## 联系

- 邮箱：1341800950@qq.com
- 仓库里的问题与建议都欢迎提 Issue
