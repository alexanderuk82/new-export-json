# Design System Tokens

Generated from Figma on 12/04/2025, 04:54:18 AM

## 📁 Structure

```
ui-system/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── breadcrumb/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── type=base,-separator=slash,-variants=base.json
│   │       ├── type=base,-separator=chevron,-variants=base.json
│   │       └── ...
│
└── README.md                   # This file
```

## 🎨 Variables (2216 total)

Design tokens exported from Figma variables:

- **Colors/Gray/50**: `#f8fafc` (color)
- **Colors/Gray/100**: `#f3f4f6` (color)
- **Colors/Gray/200**: `#e5e7eb` (color)
- **Colors/Gray/300**: `#d1d5db` (color)
- **Colors/Gray/400**: `#9ca3af` (color)
- **Colors/Gray/500**: `#6b7280` (color)
- **Colors/Gray/600**: `#4b5563` (color)
- **Colors/Gray/700**: `#374151` (color)
- **Colors/Gray/800**: `#1f2937` (color)
- **Colors/Gray/900**: `#111827` (color)

... and 2206 more

### Usage Example

```javascript
import tokens from './ui-system/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (1 total)

### Breadcrumb

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=4360:61224)
- **Variants**: 28
- **Properties**: 3
- **File**: `components/breadcrumb/metadata.json`

**Available Properties:**
- `Type`: VARIANT (Base, Bordered)
- `Separator`: VARIANT (Chevron, Slash)
- `Variants`: VARIANT (Base, Base with Dots, Links with Trigger, Links with Trigger and Label, Mobile, Desktop, Desktop with Icons)


## 🔄 Updates

This export includes:
- **2216** new variables
- **0** updated variables
- **1** new components
- **0** updated components

## 📖 How to Use

### 1. Variables/Tokens

Use the `tokens/variables.json` file to:
- Generate CSS custom properties
- Create design token configs for your framework
- Keep design and code in sync

### 2. Components

Use the `components/*/metadata.json` files to:
- Understand component structure and variants
- Generate component code scaffolding
- Document component APIs

### 3. Integration

These JSON files can be consumed by:
- **Style Dictionary** - Transform tokens to various formats
- **Storybook** - Document components
- **Custom scripts** - Generate code from metadata

---

🤖 Generated with [Design System Sync Plugin](https://github.com/your-repo)
