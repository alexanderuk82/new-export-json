# Design System Tokens

Generated from Figma on 12/04/2025, 11:49:17 AM

## 📁 Structure

```
design-tokens/new/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/

│
└── README.md                   # This file
```

## 🎨 Variables (196 total)

Design tokens exported from Figma variables:

- **global-primitive/colour/palette/red/base**: `#d50032` (color)
- **global-primitive/colour/palette/red/600**: `#d01e18` (color)
- **global-primitive/colour/palette/yellow/base**: `#ffd800` (color)
- **global-primitive/colour/palette/green/base**: `#48c748` (color)
- **global-primitive/colour/palette/blue/base**: `#0b3caa` (color)
- **global-primitive/colour/palette/gray/white**: `#fefefe` (color)
- **global-primitive/colour/palette/gray/200**: `#d7d7d9` (color)
- **global-primitive/colour/palette/gray/300**: `#b4b4b6` (color)
- **global-primitive/colour/palette/gray/800**: `#1a1a1a` (color)
- **global-primitive/colour/palette/gray/black**: `#090909` (color)

... and 186 more

### Usage Example

```javascript
import tokens from './design-tokens/new/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (0 total)



## 🔄 Updates

This export includes:
- **196** new variables
- **0** updated variables
- **0** new components
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
