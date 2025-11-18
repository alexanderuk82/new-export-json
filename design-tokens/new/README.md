# Design System Tokens

Generated from Figma on 11/18/2025, 05:31:27 AM

## 📁 Structure

```
design-tokens/new/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── navigation-icon/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── type=discover.json
│   │       ├── type=accounts.json
│   │       └── ...
│
└── README.md                   # This file
```

## 🎨 Variables (409 total)

Design tokens exported from Figma variables:

- **colour/palette/red/base**: `{colour.palette.red.base}` (color)
- **colour/palette/error/base**: `{colour.palette.error.base}` (color)
- **colour/palette/warning/base**: `{colour.palette.warning.base}` (color)
- **colour/palette/success/100**: `{colour.palette.success.100}` (color)
- **colour/palette/success/900**: `#266426` (color)
- **colour/palette/success/base**: `{colour.palette.success.base}` (color)
- **colour/palette/info/900**: `{colour.palette.info.900}` (color)
- **colour/palette/info/base**: `{colour.palette.info.base}` (color)
- **colour/palette/gray/200**: `{colour.palette.gray.200}` (color)
- **colour/palette/gray/300**: `{colour.palette.gray.300}` (color)

... and 399 more

### Usage Example

```javascript
import tokens from './design-tokens/new/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (1 total)

### Navigation Icon

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003590:259)
- **Variants**: 4
- **Properties**: 1
- **File**: `components/navigation-icon/metadata.json`

**Available Properties:**
- `Type`: VARIANT (Accounts, Discover, News, More)


## 🔄 Updates

This export includes:
- **409** new variables
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
