<p align="center">
  <a href="https://smoo.ai"><img src="https://smoo.ai/images/logo/logo.svg" alt="Smoo AI" width="220" /></a>
</p>

<h1 align="center">@smooai/config-typescript</h1>

<p align="center">
  <strong>Shared TypeScript configs that keep type checking and compilation consistent across every Smoo AI project.</strong>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@smooai/config-typescript"><img src="https://img.shields.io/npm/v/@smooai/config-typescript?style=flat-square&color=00A6A6&label=npm" alt="npm"></a>
  <img src="https://img.shields.io/badge/Smoo_AI-platform-00A6A6?style=flat-square" alt="Smoo AI">
  <img src="https://img.shields.io/badge/license-MIT-F49F0A?style=flat-square" alt="license">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
</p>

<p align="center">
  <a href="#-features">Features</a> ·
  <a href="#-install">Install</a> ·
  <a href="#-usage">Usage</a> ·
  <a href="#-part-of-smoo-ai">Platform</a>
</p>

---

> A collection of internal TypeScript configurations used across Smoo AI projects. Extend one of these `tsconfig` presets and your project inherits the same strict, modern, monorepo-friendly compiler settings we use everywhere. Derived from `@turbo/config-typescript`.

## ✨ Features

- Standard TypeScript configurations tuned for Smoo AI projects
- Strict type checking enabled by default
- Modern JavaScript feature support
- Consistent settings across every repository
- Optimized for monorepo setups
- Presets available for:
    - Node.js projects
    - React applications
    - Next.js applications
    - Library packages

## 📦 Install

```sh
pnpm add -D @smooai/config-typescript
```

This package has a peer dependency on TypeScript, so make sure it's installed too:

```sh
pnpm add -D typescript
```

## 🚀 Usage

In your `tsconfig.json`:

```json
{
    "extends": "@smooai/config-typescript/base.json"
}
```

Swap `base.json` for the preset that matches your target (Node, React, Next.js, or library).

## 🧩 Part of Smoo AI

`@smooai/config-typescript` is part of the [Smoo AI](https://smoo.ai) platform — an AI-powered business platform with AI built into every product. Browse the rest of our open-source packages at [npmjs.com/org/smooai](https://www.npmjs.com/org/smooai), including:

- [@smooai/config](https://github.com/SmooAI/config) — type-safe config, secrets, and feature flags
- [@smooai/logger](https://github.com/SmooAI/logger) — contextual logging for AWS and the browser
- [@smooai/fetch](https://github.com/SmooAI/fetch) — resilient, type-safe HTTP client

## 🤝 Contributing

Contributions are welcome. This project uses [changesets](https://github.com/changesets/changesets) to manage versions and releases.

1. Fork the repository.
2. Create your branch (`git checkout -b amazing-feature`).
3. Make your changes.
4. Add a changeset to document them: `pnpm changeset` — it prompts for the version bump type (patch, minor, or major) and a description.
5. Commit and push your branch.
6. Open a pull request, referencing any related issues.

The maintainers will review your PR and may request changes before merging.

## 📄 License

MIT © SmooAI. See [LICENSE](LICENSE).

## Contact

Brent Rager

- [Email](mailto:brent@smoo.ai)
- [LinkedIn](https://www.linkedin.com/in/brentrager/)
- [BlueSky](https://bsky.app/profile/brentragertech.bsky.social)
- [TikTok](https://www.tiktok.com/@brentragertech)
- [Instagram](https://www.instagram.com/brentragertech/)

Smoo GitHub: [github.com/SmooAI](https://github.com/SmooAI)

---

<p align="center">
  Built by <a href="https://smoo.ai"><strong>Smoo AI</strong></a> — AI built into every product.
</p>
