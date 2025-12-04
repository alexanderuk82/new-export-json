# Design System Tokens

Generated from Figma on 12/04/2025, 10:51:26 AM

## 📁 Structure

```
design-tokens/new/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── order-status/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=pending.json
│   │       ├── state=in-progress.json
│   ├── active-order/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=default.json
│   │       ├── state=loading.json
│
└── README.md                   # This file
```

## 🎨 Variables (495 total)

Design tokens exported from Figma variables:

- **colour/palette/red/base**: `{global-primitive.colour.palette.red.base}` (color)
- **colour/palette/red/600**: `{global-primitive.colour.palette.red.600}` (color)
- **colour/palette/yellow/base**: `{global-primitive.colour.palette.yellow.base}` (color)
- **colour/palette/green/100**: `{global-primitive.colour.palette.green.100}` (color)
- **colour/palette/green/900**: `#266426` (color)
- **colour/palette/green/base**: `{global-primitive.colour.palette.green.base}` (color)
- **colour/palette/blue/900**: `{global-primitive.colour.palette.blue.900}` (color)
- **colour/palette/blue/base**: `{global-primitive.colour.palette.blue.base}` (color)
- **colour/palette/gray/200**: `{global-primitive.colour.palette.gray.200}` (color)
- **colour/palette/gray/300**: `{global-primitive.colour.palette.gray.300}` (color)

... and 485 more

### Usage Example

```javascript
import tokens from './design-tokens/new/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (2 total)

### Order Status

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40004377:6184)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/order-status/metadata.json`

**Available Properties:**
- `state`: VARIANT (pending, in progress)

---

### Active Order

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40006006:1308)
- **Variants**: 2
- **Properties**: 11
- **File**: `components/active-order/metadata.json`

**Available Properties:**
- `Show Cancel Button#40006006:0`: BOOLEAN
- `Title#40006006:1`: TEXT
- `Reference#40006006:2`: TEXT
- `Type#40006006:3`: TEXT
- `Order Type#40006006:4`: TEXT
- `Quantity#40006006:5`: TEXT
- `Price#40006006:6`: TEXT
- `Date Entered#40006006:7`: TEXT
- `Expiry Date#40006006:8`: TEXT
- `Value#40006006:9`: TEXT
- `State`: VARIANT (Default, loading)


## 🔄 Updates

This export includes:
- **495** new variables
- **0** updated variables
- **2** new components
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
