# Peach X Vue3 Snippets
VSCode snippets for Peach X Vue 3 Component Library. Accelerate your development workflow with smart shortcuts.

## ✨ Features
- One-key component generation for Peach X Vue3 components
- Tab-stop support (`$1`, `$2`) for quick attribute editing
- Works in Vue Single File Components (`.vue`), `TSX`, and `JSX` files

## 📋 Snippet Shortcuts
| Component | Shortcut | Output | Description |
| --------- | -------- | ------ | ----------- |
| `p-button`  | `pxb`      | `<p-button type="primary" size="medium" @click="">$1</p-button>` | Button component |
| `p-divider` | `pxd`     | `<p-divider />` | Divider component |
| `p-ticker`  | `pxt`      | `<p-ticker :from="$1" :to="$2" />` | Animated number ticker |
| `p-config-provider` | `pxcp` | `<p-config-provider :size="$1" :theme="$2" $3>$0</p-config-provider>` | Global size/theme configuration |

*(Pro Tip: Type the shortcut and press Tab to expand)*

## 🛠 Installation
- Open VSCode Extensions (Ctrl+Shift+X)
- Search for "Peach X Vue3 Snippets"
- Click Install

## 🚀 Usage Examples
```vue
<!-- Type 'pxb' + Tab -->
<p-button>Click Me</p-button>

<!-- Type 'pxt' + Tab -->
<p-ticker :from="0" to="100" />
```