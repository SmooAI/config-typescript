---
'@smooai/config-typescript': patch
---

Use `ignoreDeprecations: '5.0'` instead of `'6.0'` in `base.json`. TS 5.x only accepts `'5.0'` as the value; `'6.0'` errors out under TS 5.x consumers (e.g. utils on TS 5.8).
