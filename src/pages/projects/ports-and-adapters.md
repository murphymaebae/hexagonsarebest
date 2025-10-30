---
layout: ../../layouts/Base.astro
title: ports & adapters sketch
description: a minimal service skeleton to start playing.
---

# ports & adapters sketch

this repo stub shows a clean separation of core logic (domain) from infrastructure (adapters).
use it as a thinking tool, not a framework.

```text
service/
├─ domain/
│  ├─ model.ts
│  └─ service.ts
├─ ports/
│  ├─ notify.ts
│  └─ store.ts
├─ adapters/
│  ├─ memory-store.ts
│  └─ console-notify.ts
└─ app.ts
```
