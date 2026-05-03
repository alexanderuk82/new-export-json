# Design System Tokens

Generated from Figma on 05/03/2026, 07:04:58 PM

## 📁 Structure

```
design-tokens/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── button/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── button=primary.json
│   │       ├── button=secondary.json
│   │       └── ...
│   ├── card/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── default.json
│
└── README.md                   # This file
```

## 🎨 Variables (45 total)

Design tokens exported from Figma variables:

- **gray/50**: `#fafafa` (color)
- **gray/100**: `#f4f4f5` (color)
- **gray/200**: `#e4e4e7` (color)
- **gray/300**: `#d4d4d8` (color)
- **gray/400**: `#a1a1aa` (color)
- **gray/500**: `#71717a` (color)
- **gray/600**: `#52525b` (color)
- **gray/700**: `#3f3f46` (color)
- **gray/800**: `#27272a` (color)
- **gray/900**: `#18181b` (color)

... and 35 more

### Usage Example

```javascript
import tokens from './design-tokens/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (2 total)

### Button

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=22:5)
- **Variants**: 3
- **Properties**: 1
- **File**: `components/button/metadata.json`

**Available Properties:**
- `Button`: VARIANT (Primary, Secondary, Ghost)

---

### Card

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=22:12)
- **Variants**: 1
- **Properties**: 0
- **File**: `components/card/metadata.json`




## 🔄 Updates

This export includes:
- **45** new variables
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
