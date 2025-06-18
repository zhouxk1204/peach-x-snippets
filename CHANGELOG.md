# Changelog

All notable changes to this project will be documented in this file.

## [0.0.3] - 2024-06-18

### Added
- New `pxb` snippet with enhanced button options
- `pxb` → `<p-button type="primary" size="medium" @click="">$1</p-button>`
  - type options: primary | info | success | warn | danger
  - size options: small | medium | large

### Fixed
- Corrected `pxt` snippet syntax (added missing colon for `:to` binding)
- Updated documentation for all snippets

## [0.0.2] - 2024-06-18

### Added
- Project logo added
- Basic documentation structure

## [0.0.1] - 2024-06-18

### Added
- Initial release of Peach X Vue3 Snippets
- Core component snippets:
  - `pxb` → `<p-button>$1</p-button>`
  - `pxd` → `<p-divider />`
  - `pxt` → `<p-ticker :from="$1" :to="$2" />`
  - `pxcp` → `<p-config-provider :size="$1" :theme="$2" $3>$0</p-config-provider>`