# My Road To LLM Architect

> 我想借助 Claude 从零开始，成为一名顶尖的 LLM 架构师。我始终相信，我可以做到任何事情。

## 关于本项目

这是一个个人学习项目，记录从零到一成为 LLM（大语言模型）架构师的完整学习路径。项目中不仅包含学习笔记与方向规划，也会将各种奇思妙想付诸实践。

## 学习路线图

### 阶段一：基础知识
- [ ] Python 编程进阶
- [ ] 线性代数、概率论与微积分基础
- [ ] 深度学习基础（神经网络、反向传播、优化器）

### 阶段二：NLP 与 Transformer
- [ ] 自然语言处理基础（分词、词嵌入、语言模型）
- [ ] Transformer 架构原理（Attention Is All You Need）
- [ ] BERT、GPT 系列模型解析

### 阶段三：大语言模型核心技术
- [ ] 预训练技术（数据处理、训练策略、分布式训练）
- [ ] 微调方法（SFT、RLHF、DPO）
- [ ] 参数高效微调（LoRA、QLoRA、Adapter）
- [ ] 提示工程（Prompt Engineering）与上下文学习

### 阶段四：模型架构设计
- [ ] LLaMA / Mistral / Qwen 等开源模型架构分析
- [ ] 注意力机制优化（FlashAttention、MQA、GQA）
- [ ] 位置编码方案（RoPE、ALiBi）
- [ ] MoE（混合专家）架构

### 阶段五：工程化与部署
- [ ] 模型量化（GPTQ、AWQ、GGUF）
- [ ] 推理优化（vLLM、TensorRT-LLM）
- [ ] RAG（检索增强生成）系统搭建
- [ ] AI Agent 架构设计与实现

### 阶段六：前沿探索
- [ ] 多模态大模型
- [ ] 长上下文处理技术
- [ ] 模型安全与对齐
- [ ] 最新论文阅读与复现

## 项目结构

本项目按主题拆分为三个分支：

| 分支 | 内容 |
|------|------|
| 分支 | 文件夹 | 说明 |
|------|--------|------|
| [`learning-and-planning`](../../tree/learning-and-planning) | `学习规划/` | 学习方向与路线规划 |
| | `资源库/` | 学习资料与参考资源 |
| | `反思/` | 阶段性总结与反思 |
| [`creative-experiments`](../../tree/creative-experiments) | `大模型/` | 大模型相关实验 |
| | `游戏/` | 游戏开发实践 |
| | `工具/` | 实用工具开发 |
| [`about-me`](../../tree/about-me) | `outlook/` | 展望与愿景（公开可见） |
| | `deepseek/` | 深度思考（仅受允许的用户可查看） |

## 技术栈

- **编程语言：** Python
- **深度学习框架：** PyTorch
- **LLM 工具：** Hugging Face Transformers, PEFT, vLLM
- **实验管理：** Jupyter Notebook
- **AI 助手：** Claude

## 如何使用

```bash
# 克隆仓库
git clone https://github.com/makoto2006598/my-road-to-llm-architect.git
cd my-road-to-llm-architect

# 创建虚拟环境（推荐）
python -m venv venv
source venv/bin/activate  # Linux/macOS
# venv\Scripts\activate   # Windows

# 安装依赖（后续会添加 requirements.txt）
pip install torch transformers jupyter
```

## 许可证

本项目采用 [MIT License](LICENSE) 开源。

---

*千里之行，始于足下。*
