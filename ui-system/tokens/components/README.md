# Design System Tokens

Generated from Figma on 10/25/2025, 08:33:01 AM

## 📁 Structure

```
ui-system/tokens/components/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── button/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state-button=primary.json
│   │       ├── state-button=secondary.json
│   │       └── ...
│   ├── input-field/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── variant=input-text.json
│   │       ├── variant=email.json
│   ├── text-area/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── variant=disable.json
│   │       ├── variant=default-with-label.json
│   │       └── ...
│   ├── label/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── variant=default.json
│   │       ├── variant=disable.json
│   ├── box/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── property-1=box-active.json
│   │       ├── property-1=box-disable.json
│
└── README.md                   # This file
```

## 🎨 Variables (53 total)

Design tokens exported from Figma variables:

- **21st-dev/Alabaster**: `#fafafa` (color)
- **21st-dev/AthensGray**: `#f4f4f5` (color)
- **21st-dev/Black**: `#030303` (color)
- **Alabaster**: `#fafafa` (color)
- **AthensGray**: `#f4f4f5` (color)
- **Black**: `#000000` (color)
- **Carnation80%**: `#f43f5ecc` (color)
- **CodGray**: `#1e1e1e` (color)
- **Concrete**: `#f3f3f3` (color)
- **Iron**: `#e4e4e7` (color)

... and 43 more

### Usage Example

```javascript
import tokens from './ui-system/tokens/components/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (5 total)

### Button

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=56:23)
- **Variants**: 6
- **Properties**: 1
- **File**: `components/button/metadata.json`

**Available Properties:**
- `state-button`: VARIANT (link, primary, secondary, destructive, outline, ghost)

---

### input-field

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=67:112)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/input-field/metadata.json`

**Available Properties:**
- `variant`: VARIANT (input-text, email)

---

### text-area

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=72:111)
- **Variants**: 4
- **Properties**: 1
- **File**: `components/text-area/metadata.json`

**Available Properties:**
- `variant`: VARIANT (default-with-label, disable, disable-with-label-disable, default)

---

### Label

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=72:122)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/label/metadata.json`

**Available Properties:**
- `variant`: VARIANT (Default, disable)

---

### box

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=72:161)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/box/metadata.json`

**Available Properties:**
- `Property 1`: VARIANT (box-active, box-disable)


## 🔄 Updates

This export includes:
- **53** new variables
- **0** updated variables
- **5** new components
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
