<div align="center">
  <img src="./whale-seascape-0.1x.png" alt="52Hz 独鲸在海面下游弋" width="1400">
  <br>
  <br>
  <img src="./whale-icon.svg" alt="52Hz 独鲸图标" width="88" height="88">
  <h1>52Hz</h1>
  <p><strong>每一种声音，都值得被听见。</strong></p>
  <p>让系统适应每个人的输入频率，理解不完整、带误触、混杂的自然语言输入。</p>
  <p>
    <a href="https://github.com/52hz-ime/52hz-docs">项目文档</a>
    ·
    <a href="https://github.com/52hz-ime/52hz-core">核心引擎</a>
    ·
    <a href="https://github.com/52hz-ime/52hz-linux-fcitx5">Linux / Fcitx5</a>
  </p>
</div>

## 关于 52Hz

52Hz 是一个以大语言模型为核心、面向自然语言表达的智能输入系统。

传统输入方式要求人先适应机器：拼音要标准，按键要准确，格式要符合规则。52Hz 希望把这种关系倒转过来：从不完整、带误触、混合中英文和符号的输入中，理解用户真正想表达的内容。

> 不同频率，也能彼此听见。

## 我们在做什么

- **理解意图**：以句子和上下文为单位处理输入，不只做逐字纠错。
- **适应设备**：把键盘布局、设备形态和个人误触习惯纳入解码。
- **自然混输**：让中文、英文、数字、符号和标点在同一句中自然共存。
- **一次成功**：优先整段完成表达，只在确有歧义时展示候选。
- **可逆可控**：自动理解和提交都能撤销、修改，并保留安全降级路径。

## 开源仓库

| 仓库 | 内容 |
| --- | --- |
| [52hz-docs](https://github.com/52hz-ime/52hz-docs) | 项目愿景、产品定义、架构和研究文档 |
| [52hz-core](https://github.com/52hz-ime/52hz-core) | 平台无关的输入运行时和核心引擎 |
| [52hz-linux-fcitx5](https://github.com/52hz-ime/52hz-linux-fcitx5) | Linux 桌面上的 Fcitx5 平台适配器 |
| [52hz-models](https://github.com/52hz-ime/52hz-models) | 模型适配、训练、转换和推理实验 |
| [52hz-eval](https://github.com/52hz-ime/52hz-eval) | 数据集、评测、基准和回归测试 |

## 当前状态

项目处于总体架构和研究方向定义阶段。当前优先在 Linux / Fcitx5 上验证设备感知的噪声拼音解码体验，再逐步扩展到其他平台。

## 品牌素材

品牌图标、透明鲸标、鲸腹版本和海景横幅统一收录在 [`52hz-docs/docs/brand`](https://github.com/52hz-ime/52hz-docs/tree/main/docs/brand)。素材沿用同一只向右游动的独鲸：用轮廓表达倾听，用留白表达跨距离沟通。

<div align="center">
  <sub>每一次输入，都值得被理解。</sub>
</div>
