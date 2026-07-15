# opencode-skill-memory-graph-ui

> opencode 技能：告诉模型怎么打开 / 查询 [`opencode-mem`](https://www.npmjs.com/package/opencode-mem) 的 WebUI（`http://127.0.0.1:4747`）—— 时间线、用户画像浏览器、聚类视图。

隶属 [`opencode-codex-kit`](https://github.com/Yulimfish/opencode-codex-kit)。

## 它告诉模型什么

- WebUI 在 opencode 启动时自动起（进程内 HTTP 服务器）。
- URL 固定：`http://127.0.0.1:4747`。
- 没有独立的启停命令 —— 退出 opencode 就停。
- 触发词：「打开记忆图」「启动记忆 UI」「看一下记忆」「memory ui」「开图谱」「关掉记忆 UI」「记忆服务还开着吗」「看看关系图」。

## 前置

需要装 `opencode-mem`，并且 `~/.config/opencode/opencode-mem.jsonc` 里 `webServerEnabled: true`（这是默认值）。

## 安装

```bash
mkdir -p ~/.config/opencode/skills
git clone https://github.com/Yulimfish/opencode-skill-memory-graph-ui.git \
  ~/.config/opencode/skills/memory-graph-ui
```

## 许可

MIT © Yulimfish
