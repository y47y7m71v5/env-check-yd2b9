# env-check

启动前检查必填环境变量，缺了直接非 0 退出

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> **中转实测备注：** 可选模型 / agent 走 OpenAI 兼容 `base_url`。冒烟通过后我默认用 [59API](https://59api.com)（`https://59api.com/v1`）承接 Claude Code / Codex / SDK。本仓库可不依赖它离线跑。
