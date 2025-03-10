<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<br />
<div align="center">
  <a href="https://smoo.ai">
    <img src="images/logo.png" alt="SmooAI Logo" />
  </a>
</div>

<!-- ABOUT THE PROJECT -->

## About SmooAI

SmooAI is an AI-powered platform for helping businesses multiply their customer, employee, and developer experience.

Learn more on [smoo.ai](https://smoo.ai)

## SmooAI Packages

Check out other SmooAI packages at [npmjs.com/org/smooai](https://www.npmjs.com/org/smooai)

## About @smooai/config-typescript

Collection of internal TypeScript configurations used across SmooAI projects. This package provides standardized TypeScript configurations to ensure consistent type checking and compilation settings across all SmooAI repositories.

Derived from `@turbo/config-typescript`.

![NPM Version](https://img.shields.io/npm/v/%40smooai%2Fconfig-typescript?style=for-the-badge)
![NPM Downloads](https://img.shields.io/npm/dw/%40smooai%2Fconfig-typescript?style=for-the-badge)
![NPM Last Update](https://img.shields.io/npm/last-update/%40smooai%2Fconfig-typescript?style=for-the-badge)

![GitHub License](https://img.shields.io/github/license/SmooAI/config-typescript?style=for-the-badge)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/SmooAI/config-typescript/release.yml?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/SmooAI/config-typescript?style=for-the-badge)

### Installation

```sh
pnpm add -D @smooai/config-typescript
```

Note: This package has a peer dependency on TypeScript. Make sure you have TypeScript installed in your project:

```sh
pnpm add -D typescript
```

### Usage

In your `tsconfig.json`:

```json
{
    "extends": "@smooai/config-typescript/base.json"
}
```

### Features

- Standard TypeScript configurations optimized for SmooAI projects
- Strict type checking enabled
- Modern JavaScript features support
- Consistent configuration across projects
- Optimized for monorepo setups
- Configurations available for:
    - Node.js projects
    - React applications
    - Next.js applications
    - Library packages

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are welcome! This project uses [changesets](https://github.com/changesets/changesets) to manage versions and releases.

### Development Workflow

1. Fork the repository
2. Create your branch (`git checkout -b amazing-feature`)
3. Make your changes
4. Add a changeset to document your changes:

    ```sh
    pnpm changeset
    ```

    This will prompt you to:

    - Choose the type of version bump (patch, minor, or major)
    - Provide a description of the changes

5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Pull Request Guidelines

- Reference any related issues in your PR description

The maintainers will review your PR and may request changes before merging.

<!-- CONTACT -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Brent Rager

- [Email](mailto:brent@smoo.ai)
- [LinkedIn](https://www.linkedin.com/in/brentrager/)
- [BlueSky](https://bsky.app/profile/brentragertech.bsky.social)
- [TikTok](https://www.tiktok.com/@brentragertech)
- [Instagram](https://www.instagram.com/brentragertech/)

Smoo Github: [https://github.com/SmooAI](https://github.com/SmooAI)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
