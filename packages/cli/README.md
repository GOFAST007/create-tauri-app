<img src="https://github.com/tauri-apps/create-tauri-app/raw/dev/.github/splash.png" alt="Rapidly scaffold out a new Tauri app project." />

[![](https://img.shields.io/crates/v/create-tauri-app)](https://crates.io/crates/create-tauri-app)
[![](https://img.shields.io/npm/v/create-tauri-app.svg)](https://www.npmjs.com/package/create-tauri-app)
[![status](https://img.shields.io/badge/status-stable-blue.svg)](https://github.com/tauri-apps/tauri)
[![Chat Server](https://img.shields.io/badge/chat-discord-7289da.svg)](https://discord.gg/SpmNs4S)
[![website](https://img.shields.io/badge/website-tauri.app-purple.svg)](https://tauri.app)
[![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)
[![support](https://img.shields.io/badge/sponsor-Open%20Collective-blue.svg)](https://opencollective.com/tauri)


## Usage

With Cargo:

``` bash
cargo install create-tauri-app
cargo create-tauri-app
```

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + Vue project, run:

```bash
cargo create-tauri-app --template svelte
```

Currently supported template presets include:

- `vanilla`
- `vue`
- `vue-ts`
- `react`
- `react-ts`
- `svelte`
- `svelte-ts`
- `solid`
- `solid-ts`
- `yew`
- `next`
- `next-ts`

You can use `.` for the project name to scaffold in the current directory.

## Semver
**create-tauri-app** is following [Semantic Versioning 2.0](https://semver.org/).

## Licenses
Code: (c) 2022 - The Tauri Programme within The Commons Conservancy.

MIT or MIT/Apache 2.0 where applicable.

Logo: CC-BY-NC-ND
- Original Tauri Logo Designs by [Daniel Thompson-Yvetot](https://github.com/nothingismagick) and [Guillaume Chau](https://github.com/akryum)