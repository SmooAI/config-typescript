---
'@smooai/config-typescript': patch
---

Add `ignoreDeprecations: '6.0'` to `base.json` so consumer packages with `baseUrl` don't fail typecheck on newer TypeScript versions. TS 6.x escalates `baseUrl` from a warning to a deprecation error.
