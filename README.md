Devtoolster
===
[![LICENSE](https://img.shields.io/github/license/timo-reymann/devtoolster)](https://github.com/timo-reymann/devtoolster/blob/main/LICENSE)
[![CircleCI](https://circleci.com/gh/timo-reymann/devtoolster.svg?style=shield)](https://app.circleci.com/pipelines/github/timo-reymann/devtoolster)
[![GitHub Release](https://img.shields.io/github/v/tag/timo-reymann/devtoolster?label=version)](https://github.com/timo-reymann/devtoolster/releases)
[![Renovate](https://img.shields.io/badge/renovate-enabled-green?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzNjkgMzY5Ij48Y2lyY2xlIGN4PSIxODkuOSIgY3k9IjE5MC4yIiByPSIxODQuNSIgZmlsbD0iI2ZmZTQyZSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTUgLTYpIi8+PHBhdGggZmlsbD0iIzhiYjViNSIgZD0iTTI1MSAyNTZsLTM4LTM4YTE3IDE3IDAgMDEwLTI0bDU2LTU2YzItMiAyLTYgMC03bC0yMC0yMWE1IDUgMCAwMC03IDBsLTEzIDEyLTktOCAxMy0xM2ExNyAxNyAwIDAxMjQgMGwyMSAyMWM3IDcgNyAxNyAwIDI0bC01NiA1N2E1IDUgMCAwMDAgN2wzOCAzOHoiLz48cGF0aCBmaWxsPSIjZDk1NjEyIiBkPSJNMzAwIDI4OGwtOCA4Yy00IDQtMTEgNC0xNiAwbC00Ni00NmMtNS01LTUtMTIgMC0xNmw4LThjNC00IDExLTQgMTUgMGw0NyA0N2M0IDQgNCAxMSAwIDE1eiIvPjxwYXRoIGZpbGw9IiMyNGJmYmUiIGQ9Ik04MSAxODVsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzI1YzRjMyIgZD0iTTIyMCAxMDBsMjMgMjNjNCA0IDQgMTEgMCAxNkwxNDIgMjQwYy00IDQtMTEgNC0xNSAwbC0yNC0yNGMtNC00LTQtMTEgMC0xNWwxMDEtMTAxYzUtNSAxMi01IDE2IDB6Ii8+PHBhdGggZmlsbD0iIzFkZGVkZCIgZD0iTTk5IDE2N2wxOC0xOCAxOCAxOC0xOCAxOHoiLz48cGF0aCBmaWxsPSIjMDBhZmIzIiBkPSJNMjMwIDExMGwxMyAxM2M0IDQgNCAxMSAwIDE2TDE0MiAyNDBjLTQgNC0xMSA0LTE1IDBsLTEzLTEzYzQgNCAxMSA0IDE1IDBsMTAxLTEwMWM1LTUgNS0xMSAwLTE2eiIvPjxwYXRoIGZpbGw9IiMyNGJmYmUiIGQ9Ik0xMTYgMTQ5bDE4LTE4IDE4IDE4LTE4IDE4eiIvPjxwYXRoIGZpbGw9IiMxZGRlZGQiIGQ9Ik0xMzQgMTMxbDE4LTE4IDE4IDE4LTE4IDE4eiIvPjxwYXRoIGZpbGw9IiMxYmNmY2UiIGQ9Ik0xNTIgMTEzbDE4LTE4IDE4IDE4LTE4IDE4eiIvPjxwYXRoIGZpbGw9IiMyNGJmYmUiIGQ9Ik0xNzAgOTVsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzFiY2ZjZSIgZD0iTTYzIDE2N2wxOC0xOCAxOCAxOC0xOCAxOHpNOTggMTMxbDE4LTE4IDE4IDE4LTE4IDE4eiIvPjxwYXRoIGZpbGw9IiMzNGVkZWIiIGQ9Ik0xMzQgOTVsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzFiY2ZjZSIgZD0iTTE1MyA3OGwxOC0xOCAxOCAxOC0xOCAxOHoiLz48cGF0aCBmaWxsPSIjMzRlZGViIiBkPSJNODAgMTEzbDE4LTE3IDE4IDE3LTE4IDE4ek0xMzUgNjBsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzk4ZWRlYiIgZD0iTTI3IDEzMWwxOC0xOCAxOCAxOC0xOCAxOHoiLz48cGF0aCBmaWxsPSIjYjUzZTAyIiBkPSJNMjg1IDI1OGw3IDdjNCA0IDQgMTEgMCAxNWwtOCA4Yy00IDQtMTEgNC0xNiAwbC02LTdjNCA1IDExIDUgMTUgMGw4LTdjNC01IDQtMTIgMC0xNnoiLz48cGF0aCBmaWxsPSIjOThlZGViIiBkPSJNODEgNzhsMTgtMTggMTggMTgtMTggMTh6Ii8+PHBhdGggZmlsbD0iIzAwYTNhMiIgZD0iTTIzNSAxMTVsOCA4YzQgNCA0IDExIDAgMTZMMTQyIDI0MGMtNCA0LTExIDQtMTUgMGwtOS05YzUgNSAxMiA1IDE2IDBsMTAxLTEwMWM0LTQgNC0xMSAwLTE1eiIvPjxwYXRoIGZpbGw9IiMzOWQ5ZDgiIGQ9Ik0yMjggMTA4bC04LThjLTQtNS0xMS01LTE2IDBMMTAzIDIwMWMtNCA0LTQgMTEgMCAxNWw4IDhjLTQtNC00LTExIDAtMTVsMTAxLTEwMWM1LTQgMTItNCAxNiAweiIvPjxwYXRoIGZpbGw9IiNhMzM5MDQiIGQ9Ik0yOTEgMjY0bDggOGM0IDQgNCAxMSAwIDE2bC04IDdjLTQgNS0xMSA1LTE1IDBsLTktOGM1IDUgMTIgNSAxNiAwbDgtOGM0LTQgNC0xMSAwLTE1eiIvPjxwYXRoIGZpbGw9IiNlYjZlMmQiIGQ9Ik0yNjAgMjMzbC00LTRjLTYtNi0xNy02LTIzIDAtNyA3LTcgMTcgMCAyNGw0IDRjLTQtNS00LTExIDAtMTZsOC04YzQtNCAxMS00IDE1IDB6Ii8+PHBhdGggZmlsbD0iIzEzYWNiZCIgZD0iTTEzNCAyNDhjLTQgMC04LTItMTEtNWwtMjMtMjNhMTYgMTYgMCAwMTAtMjNMMjAxIDk2YTE2IDE2IDAgMDEyMiAwbDI0IDI0YzYgNiA2IDE2IDAgMjJMMTQ2IDI0M2MtMyAzLTcgNS0xMiA1em03OC0xNDdsLTQgMi0xMDEgMTAxYTYgNiAwIDAwMCA5bDIzIDIzYTYgNiAwIDAwOSAwbDEwMS0xMDFhNiA2IDAgMDAwLTlsLTI0LTIzLTQtMnoiLz48cGF0aCBmaWxsPSIjYmY0NDA0IiBkPSJNMjg0IDMwNGMtNCAwLTgtMS0xMS00bC00Ny00N2MtNi02LTYtMTYgMC0yMmw4LThjNi02IDE2LTYgMjIgMGw0NyA0NmM2IDcgNiAxNyAwIDIzbC04IDhjLTMgMy03IDQtMTEgNHptLTM5LTc2Yy0xIDAtMyAwLTQgMmwtOCA3Yy0yIDMtMiA3IDAgOWw0NyA0N2E2IDYgMCAwMDkgMGw3LThjMy0yIDMtNiAwLTlsLTQ2LTQ2Yy0yLTItMy0yLTUtMnoiLz48L3N2Zz4=)](https://renovatebot.com)

<p align="center">
	<img width="300" src="./.github/images/logo.png">
    <br />
    Register custom DevTools panels from any web application — no overlays, no hacks.
</p>

> :construction: This project is under active development. Expect rough edges, missing features, and breaking changes.

## Features

- **Native DevTools panel** — a custom _Devtoolster_ tab alongside the built-in Chrome/Firefox DevTools
- **Simple page-facing API** — `@devtoolster/web-api` lets any web app register controls via `window.postMessage`
- **Rich control types** — buttons, text inputs, dropdowns, color pickers, toggles, sliders, and data tables
- **Cross-browser** — Chrome and Firefox, both built from a single WXT config
- **Tab-based organisation** — group registered controls into named tabs within the panel

## Requirements

- Node.js 18+ and npm / yarn
- Chrome 88+ or Firefox 109+ (Manifest V3)

## Installation

```bash
npm install
```

## Usage

### Run the extension (development)

```bash
npm run dev            # Chrome
npm run dev:firefox    # Firefox
```

### Build for production

```bash
npm run build          # -> extension/.output/chrome-mv3
npm run build:firefox  # -> extension/.output/firefox-mv3
```

### Open the demo

```bash
npm run demo           # serves http://localhost:8080
```

Then open DevTools → _Devtoolster_ tab.

## Background

In larger or enterprise web applications, development and QA often requires adjusting values or mocking state to demonstrate behaviour to stakeholders. Framework-provided tools are sometimes enough, but frequently cumbersome. Many teams end up writing their own dev tools — page overlays, query-parameter toggles, step-by-step guides bolted onto existing panels.

## Motivation

All of those approaches require effort that isn't always justified. Devtoolster aims to provide a slim, consistent API that lets any web application register custom controls inside the browser's native DevTools with minimal setup.

## Implementation

![](./docs/implementation.png)

The extension is built with [WXT](https://wxt.dev) (Vite-based) in TypeScript, with a Svelte-based DevTools panel. WXT generates the Chrome (`service_worker`) and Firefox (`background.scripts`) Manifest V3 files from a single config — no manual per-browser manifest swap. The page-facing API lives in `@devtoolster/web-api`, a TypeScript package built with Vite (library mode) and published through the same npm workspace.

### Application side

- Typed TypeScript API (`@devtoolster/web-api`) wrapping `window.postMessage`
- Talks to the content script via window messaging

### Extension

- **Content script** — injected into the page, bridges `window` messaging to the extension runtime
- **Background worker** — routes messages between the content script and the DevTools panel
- **DevTools panel** — registers the _Devtoolster_ tab, listens for `devtools:open`, and renders controls registered by the application

## Screenshots

### Chrome

| Dark | Light |
|------|-------|
| ![](./docs/chrome_dark.png) | ![](./docs/chrome_light.png) |

### Firefox

| Dark | Light |
|------|-------|
| ![](./docs/firefox_dark.png) | ![](./docs/firefox_light.png) |

## Known limitations

- No keyboard shortcuts or focus management
- No sorting or filtering for table data
- Stale panel content persists when navigating to a page without a matching content script (e.g. `chrome://`, `about:`, or pages that don't inject the content script)

## Planned / in progress

- Proper error handling and user-facing error states
- More UI controls (toggles, sliders, color pickers, …)
- Automated tests (e2e and unit)
- User approval prompt — per-session consent before the panel activates

## Documentation

- [Privacy policy](./PRIVACY.md)

## Contributing

I love your input! I want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the configuration
- Submitting a fix
- Proposing new features
- Becoming a maintainer

To get started please read the [Contribution Guidelines](./CONTRIBUTING.md).

## Development

### Requirements

- Node.js 18+
- npm
- Chrome or Firefox

### Smoke test checklist

After loading the extension and opening the demo page + DevTools panel:

- [ ] Tab bar shows two tabs: **Table** and **Controls**
- [ ] Clicking each tab switches the visible content
- [ ] The active tab has a highlighted bottom border
- [ ] **Controls** tab: Headings "Communication" and "Manipulate page" are visible
- [ ] **Controls** tab: "Hi from your todays host" button triggers an alert dialog
- [ ] **Controls** tab: "Log it baby one more time" logs to the page's console
- [ ] **Controls** tab: Dropdown "Select something" sends a selection event
- [ ] **Controls** tab: "Set random background" changes the page background color
- [ ] **Controls** tab: "Your name here" input submits the typed value
- [ ] **Controls** tab: Color picker "Overwrite background color" works
- [ ] **Table** tab: Table with columns Name/Age/City and 3 rows is visible
- [ ] **Controls** tab: "Cycle table data" button — switch to **Table** tab to see data change
- [ ] **Controls** tab: Unsupported element `{type: "test"}` logs an error (expected)
- [ ] Reloading the page (F5) resets and re-registers all controls under both tabs
- [ ] No "message port closed before a response was received" warnings in the background service-worker console (Chrome: inspect service worker from `chrome://extensions`)

