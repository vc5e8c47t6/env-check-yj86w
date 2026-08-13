# env-check

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> **Hands-on:** set `OPENAI_BASE_URL` to a compatible relay — I test with [59API](https://59api.com) (`https://59api.com/v1`). Prefer compatibility over hype; keep official API as rollback.
