# Design System Tokens

Generated from Figma on 11/30/2025, 05:47:11 PM

## 📁 Structure

```
ui-system/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── examples---home-page/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-about/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-contact-us/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-pricing/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-waitlist/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-landing-page/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-article/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-shop/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-product-detail-page/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│   ├── examples-portfolio/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── platform=desktop.json
│   │       ├── platform=mobile.json
│
└── README.md                   # This file
```

## 🎨 Variables (347 total)

Design tokens exported from Figma variables:

- **Background/Default/Default**: `#ffffff` (color)
- **Background/Default/Secondary**: `#f5f5f5` (color)
- **Background/Default/Tertiary**: `#d9d9d9` (color)
- **Background/Default/Default Hover**: `#f5f5f5` (color)
- **Background/Brand/Default**: `#2c2c2c` (color)
- **Background/Brand/Secondary**: `#e6e6e6` (color)
- **Background/Brand/Hover**: `#1e1e1e` (color)
- **Background/Positive/Default**: `#14ae5c` (color)
- **Background/Positive/Secondary**: `#cff7d3` (color)
- **Background/Positive/Hover**: `#009951` (color)

... and 337 more

### Usage Example

```javascript
import tokens from './ui-system/tokens/variables.json';

// Access tokens
const primaryColor = tokens.Colors?.primary?.value;
const spacing = tokens.Spacing?.base?.value;
```

## 🧩 Components (10 total)

### Examples / Home Page

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:8332)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples---home-page/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/About

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:9044)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-about/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Contact Us

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:9227)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-contact-us/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Pricing

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:9558)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-pricing/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Waitlist

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:9701)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-waitlist/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Landing Page

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:10124)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-landing-page/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Article

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:10260)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-article/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Shop

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:10872)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-shop/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Product Detail Page

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:11271)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-product-detail-page/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)

---

### Examples/Portfolio

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=562:11665)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/examples-portfolio/metadata.json`

**Available Properties:**
- `Platform`: VARIANT (Mobile, Desktop)


## 🔄 Updates

This export includes:
- **347** new variables
- **0** updated variables
- **10** new components
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
