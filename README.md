# Minimal UX Motion Guard

> **用尽量少的注意力，创造更多的价值。**
> 一套面向 AI 产品与前端界面的极简交互重构、状态连续性动效打磨与 Agent 工程容错审查技能。

## 核心能力

- **前置按需分流**：自动识别 `0 -> 1 新建架构` 与 `局部页面/组件审查`，拒绝无效流程干扰。
- **3 秒盲看与交互减法**：砍除解释性拐杖文案、重复入口与零状态噪音，让空间布局自己说明自己。
- **状态驱动动效基线**：按状态跃迁而非部件检索动效，内置 `120-240ms` 与 `cubic-bezier(0.22, 1, 0.36, 1)` 满帧合成层约束。
- **Agent 三态与兜底三件套**：强制覆盖流式反馈、随时中断与超时无声降级，自动维护 `INTERACTION_LEDGER.md` 交互账本。

## 快速安装

### 方式 1：通过 Skills CLI 一键安装（支持 Claude Code / Cursor / Codex）
~~~bash
npx skills add AdgaiWalker/minimal-ux-motion-guard
~~~

### 方式 2：手动放入本地技能目录
~~~bash
mkdir -p ~/.claude/skills/minimal-ux-motion-guard
curl -fsSL https://raw.githubusercontent.com/AdgaiWalker/minimal-ux-motion-guard/main/SKILL.md \
  -o ~/.claude/skills/minimal-ux-motion-guard/SKILL.md
~~~

## 触发示例

- *"用极简交互原则审查这张页面截图，做一次 3 秒盲看测试。"*
- *"按状态变化检查这个组件的动效，补齐 Agent 超时无声降级方案。"*

## License

MIT
