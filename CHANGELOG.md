# Changelog

## [0.6.3](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/compare/v0.6.2...v0.6.3) (2026-11-19)


### Bug Fixes

* **deps:** bump @hono/node-server from 2.1.5 to 2.1.8 ([#38](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/issues/38)) ([35a3fdb](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/commit/35a3fdbd6c0ee8dc11f2857c632b3bc22a9a2362))
* **deps:** bump hono from 4.13.13 to 4.13.18 ([#39](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/issues/39)) ([d5ac59f](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/commit/d5ac59fc5fca8ca8ae2f3dc23528c9565ed87ad0))
* **deps:** bump minimatch, eslint and typescript-eslint ([#44](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/issues/44)) ([e1ac218](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/commit/e1ac2180008b581b925c05fb833e2ebca71d8120))
* **deps:** bump undici from 8.12.3 to 8.12.4 in the runtime group ([#40](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/issues/40)) ([2cf98d7](https://github.com/Tracht-Digital-Labs/gitea-claude-plugin/commit/2cf98d729588aacf265e56216b6119dadfe99d1a))

## [0.6.2](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/compare/v0.6.1...v0.6.2) (2026-11-03)


### Miscellaneous

* release 0.6.2 ([b302aa6](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/commit/b302aa6d5985d13e2b2298683427e4748ae7c7dc))

## [0.6.1](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/compare/v0.6.0...v0.6.1) (2026-11-02)


### Bug Fixes

* **deps:** bump @modelcontextprotocol/sdk ([#30](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/issues/30)) ([978c1e8](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/commit/978c1e8010920bbd59ef96039db7171be2b63aa2))
* **deps:** bump body-parser from 2.3.0 to 2.4.0 ([#29](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/issues/29)) ([ce8816d](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/commit/ce8816d75a988092ff3fe94b75a20c4fb48ad373))

## [0.6.0](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/compare/v0.5.2...v0.6.0) (2026-10-22)


### ⚠ BREAKING CHANGES

* the marketplace is renamed from jtracht-gitea to tds-gitea. Remove the jtracht-gitea marketplace, add Tracht-Digital-Solutions/gitea-claude-plugin and install gitea@tds-gitea.

### Miscellaneous

* move repository to Tracht-Digital-Solutions ([#27](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/issues/27)) ([21e6a2e](https://github.com/Tracht-Digital-Solutions/gitea-claude-plugin/commit/21e6a2e2d882e34fa8b0060b955b770c5c7d16f3))

## [0.5.2](https://github.com/jtracht/gitea-claude-plugin/compare/v0.5.1...v0.5.2) (2026-10-21)


### Miscellaneous

* release 0.5.2 ([#25](https://github.com/jtracht/gitea-claude-plugin/issues/25)) ([fbe58ed](https://github.com/jtracht/gitea-claude-plugin/commit/fbe58ed15c1f11c15eecc4b994fb81fa695d1dbb))

## [0.5.1](https://github.com/jtracht/claude-code-gitea/compare/v0.5.0...v0.5.1) (2026-10-21)


### Refactoring

* restructure the server and share helpers across tool modules ([#21](https://github.com/jtracht/claude-code-gitea/issues/21)) ([fa1a562](https://github.com/jtracht/claude-code-gitea/commit/fa1a5625d49ec9c726255024caba9f25cb380dfe))

## [0.5.0](https://github.com/jtracht/claude-code-gitea/compare/v0.4.1...v0.5.0) (2026-10-21)


### Features

* **projects:** reorder project columns and report inherited Actions runners ([#19](https://github.com/jtracht/claude-code-gitea/issues/19)) ([b3f35a2](https://github.com/jtracht/claude-code-gitea/commit/b3f35a25e781f50630d07a5e22983b0e58d8e692))

## [0.4.1](https://github.com/jtracht/claude-code-gitea/compare/v0.4.0...v0.4.1) (2026-10-21)


### Bug Fixes

* **releases:** treat every SemVer pre-release suffix as a pre-release ([#16](https://github.com/jtracht/claude-code-gitea/issues/16)) ([903f56d](https://github.com/jtracht/claude-code-gitea/commit/903f56dbccced826feeb0a3db5ac49fb7be63b7e))

## [0.4.0](https://github.com/jtracht/claude-code-gitea/compare/v0.3.0...v0.4.0) (2026-10-21)


### Features

* add time tracking, wiki, package and runner tools ([#14](https://github.com/jtracht/claude-code-gitea/issues/14)) ([f3c996e](https://github.com/jtracht/claude-code-gitea/commit/f3c996ed59373a71815df69792b3a82b835224ed))

## [0.3.0](https://github.com/jtracht/claude-code-gitea/compare/v0.2.1...v0.3.0) (2026-10-21)


### Features

* **projects:** add project board tools ([#12](https://github.com/jtracht/claude-code-gitea/issues/12)) ([6095b03](https://github.com/jtracht/claude-code-gitea/commit/6095b0314a844a4faab2ea68867f737830846cbd))

## [0.2.1](https://github.com/jtracht/claude-code-gitea/compare/v0.2.0...v0.2.1) (2026-10-21)


### Bug Fixes

* **plugin:** recommend the write:user token scope needed to create repositories ([#10](https://github.com/jtracht/claude-code-gitea/issues/10)) ([1e90785](https://github.com/jtracht/claude-code-gitea/commit/1e9078529f1f2dfdfcadf449dc6449f497b94e1b))

## 0.2.0 (2026-10-21)

First published release.


### Features

* **core:** add Gitea HTTP client, configuration and security primitives ([6966e20](https://github.com/jtracht/claude-code-gitea/commit/6966e20781aebfaa765c8a117f632040c5bf83fe))
* **plugin:** add Claude Code plugin manifest and bundled MCP server build ([d112382](https://github.com/jtracht/claude-code-gitea/commit/d1123826b4944815fdefb0c878f8160dc93ef6b5))
* **plugin:** add workflow skills, marketplace and icon ([c60756f](https://github.com/jtracht/claude-code-gitea/commit/c60756f6799b5b4deff8d801c74a072bc257947f))
* **tools:** add MCP server and Gitea tool modules ([bcdf8d8](https://github.com/jtracht/claude-code-gitea/commit/bcdf8d8b8bab619576d8d5d1a6be90b27c567fe4))


### Bug Fixes

* **plugin:** ship the release skill ([#6](https://github.com/jtracht/claude-code-gitea/issues/6)) ([a622c36](https://github.com/jtracht/claude-code-gitea/commit/a622c36c30b5295aa5333975e3b0267d6fa62fb3))


### Documentation

* add README, German docs, architecture, configuration and community files ([719b36d](https://github.com/jtracht/claude-code-gitea/commit/719b36da5c122c1efc8fa4ef3a3e2bf986686e62))

## 0.1.0 (2026-10-21)

> Not published. The release pipeline was stopped before publication and the draft was withdrawn
> because the `release` skill was missing from the package; 0.2.0 is the first published version.


### Features

* **core:** add Gitea HTTP client, configuration and security primitives ([6966e20](https://github.com/jtracht/claude-code-gitea/commit/6966e20781aebfaa765c8a117f632040c5bf83fe))
* **plugin:** add Claude Code plugin manifest and bundled MCP server build ([d112382](https://github.com/jtracht/claude-code-gitea/commit/d1123826b4944815fdefb0c878f8160dc93ef6b5))
* **plugin:** add workflow skills, marketplace and icon ([c60756f](https://github.com/jtracht/claude-code-gitea/commit/c60756f6799b5b4deff8d801c74a072bc257947f))
* **tools:** add MCP server and Gitea tool modules ([bcdf8d8](https://github.com/jtracht/claude-code-gitea/commit/bcdf8d8b8bab619576d8d5d1a6be90b27c567fe4))


### Documentation

* add README, German docs, architecture, configuration and community files ([719b36d](https://github.com/jtracht/claude-code-gitea/commit/719b36da5c122c1efc8fa4ef3a3e2bf986686e62))

## Changelog

All notable changes to this project are documented in this file. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project uses
[Semantic Versioning](https://semver.org). Entries are generated by
[Release Please](https://github.com/googleapis/release-please) from Conventional Commits.
