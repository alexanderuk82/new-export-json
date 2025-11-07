# Design System Tokens

Generated from Figma on 11/07/2025, 03:31:35 AM

## 📁 Structure

```
ui-system/tokens/components/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── alert/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── size=default,-variant=solid,-status=error.json
│   │       ├── size=default,-variant=solid,-status=neutral.json
│   │       └── ...
│   ├── alert/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── size=default,-variant=solid,-status=error.json
│   │       ├── size=default,-variant=solid,-status=neutral.json
│   │       └── ...
│
└── README.md                   # This file
```

## 🎨 Variables (389 total)

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

... and 379 more

### Usage Example

```javascript
import tokens from './ui-system/tokens/components/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (2 total)

### Alert

Used to communicate a state that affects a system, feature or page.

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=130:2296)
- **Variants**: 60
- **Properties**: 8
- **File**: `components/alert/metadata.json`

**Available Properties:**
- `description#130:0`: BOOLEAN
- `indicator/info#143:190`: INSTANCE_SWAP
- `indicator/warning#143:251`: INSTANCE_SWAP
- `indicator/success#143:312`: INSTANCE_SWAP
- `indicator/custom#143:373`: INSTANCE_SWAP
- `size`: VARIANT (Default, md, lg)
- `variant`: VARIANT (solid, subtle, surface, outline)
- `status`: VARIANT (error, info, warning, success, neutral)

---

### Alert

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=143:3735)
- **Variants**: 60
- **Properties**: 8
- **File**: `components/alert/metadata.json`

**Available Properties:**
- `description#130:0`: BOOLEAN
- `indicator/info#143:190`: INSTANCE_SWAP
- `indicator/warning#143:251`: INSTANCE_SWAP
- `indicator/success#143:312`: INSTANCE_SWAP
- `indicator/custom#143:373`: INSTANCE_SWAP
- `size`: VARIANT (Default, md, lg)
- `variant`: VARIANT (solid, subtle, surface, outline)
- `status`: VARIANT (error, info, warning, success, neutral)


## 🔄 Updates

This export includes:
- **389** new variables
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
