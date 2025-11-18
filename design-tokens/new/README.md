# Design System Tokens

Generated from Figma on 11/18/2025, 03:09:50 PM

## 📁 Structure

```
design-tokens/new/
├── tokens/
│   └── variables.json          # All design tokens (colors, spacing, typography, etc.)
│
├── components/
│   ├── tabs.trigger/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=selected.json
│   │       ├── state=focus.json
│   │       └── ...
│   ├── segmentindicator/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=active.json
│   │       ├── state=inactive.json
│   │       └── ...
│   ├── header-cells/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── type=startalign.json
│   │       ├── type=endalign.json
│   │       └── ...
│   ├── data-cells/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── type=startalign.json
│   │       ├── type=endalign.json
│   ├── progressbar/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=in-progress.json
│   │       ├── state=empty.json
│   │       └── ...
│   ├── draweritem/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── variant=item.json
│   │       ├── variant=toggle.json
│   │       └── ...
│   ├── portfoliolistitem/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=simple.json
│   │       ├── state=detailed.json
│   ├── portfoliolist/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=default.json
│   │       ├── state=empty.json
│   ├── dropdownfilter/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=enabled.json
│   │       ├── state=active.json
│   │       └── ...
│   ├── topnav/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=top.json
│   │       ├── state=scrolled.json
│   ├── activity-list-item/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── type=transaction.json
│   │       ├── type=order.json
│   ├── activity-list/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=default.json
│   │       ├── state=empty.json
│   ├── ghostfilter/
│   │   ├── metadata.json       # Component documentation
│   │   ├── tokens.json         # Design tokens used by this component
│   │   └── variants/           # Individual variant specifications
│   │       ├── state=active.json
│   │       ├── state=disabled.json
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

## 🧩 Components (13 total)

### Tabs.Trigger

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003172:7532)
- **Variants**: 6
- **Properties**: 2
- **File**: `components/tabs.trigger/metadata.json`

**Available Properties:**
- `Label#40003334:0`: TEXT
- `state`: VARIANT (selected, focus, inactive, hover, pressed, disabled)

---

### SegmentIndicator

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003185:4667)
- **Variants**: 3
- **Properties**: 1
- **File**: `components/segmentindicator/metadata.json`

**Available Properties:**
- `state`: VARIANT (active, inactive, disabled)

---

### Header Cells

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003172:12789)
- **Variants**: 3
- **Properties**: 2
- **File**: `components/header-cells/metadata.json`

**Available Properties:**
- `Header#40003664:3`: TEXT
- `type`: VARIANT (checkbox, endAlign, startAlign)

---

### Data Cells

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003172:12764)
- **Variants**: 2
- **Properties**: 3
- **File**: `components/data-cells/metadata.json`

**Available Properties:**
- `Show Icon after#40003191:38`: BOOLEAN
- `Text#40003664:0`: TEXT
- `type`: VARIANT (endAlign, startAlign)

---

### ProgressBar

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003367:8810)
- **Variants**: 3
- **Properties**: 1
- **File**: `components/progressbar/metadata.json`

**Available Properties:**
- `State`: VARIANT (empty, in progress, complete)

---

### DrawerItem

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003427:3423)
- **Variants**: 3
- **Properties**: 3
- **File**: `components/draweritem/metadata.json`

**Available Properties:**
- `Title#40003427:0`: TEXT
- `Description#40003427:4`: TEXT
- `Variant`: VARIANT (item, radio, toggle)

---

### PortfolioListItem

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003465:7623)
- **Variants**: 2
- **Properties**: 4
- **File**: `components/portfoliolistitem/metadata.json`

**Available Properties:**
- `Name#40003465:8`: TEXT
- `Ticker#40003465:9`: TEXT
- `Value#40003664:11`: TEXT
- `State`: VARIANT (Simple, Detailed)

---

### PortfolioList

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003540:2903)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/portfoliolist/metadata.json`

**Available Properties:**
- `State`: VARIANT (Default, Empty)

---

### DropDownFilter

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003540:3057)
- **Variants**: 3
- **Properties**: 2
- **File**: `components/dropdownfilter/metadata.json`

**Available Properties:**
- `input-content#40003664:7`: TEXT
- `State`: VARIANT (Enabled, Active, Disabled)

---

### TopNav

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003547:3052)
- **Variants**: 2
- **Properties**: 3
- **File**: `components/topnav/metadata.json`

**Available Properties:**
- `Account Name#40003706:0`: TEXT
- `Account Holder Name#40003706:3`: TEXT
- `State`: VARIANT (Top, Scrolled)

---

### Activity List item

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003549:5948)
- **Variants**: 2
- **Properties**: 6
- **File**: `components/activity-list-item/metadata.json`

**Available Properties:**
- `Name#40003702:6`: TEXT
- `Reference Number#40003702:9`: TEXT
- `Quantity Value#40003702:12`: TEXT
- `Price Value#40003702:15`: TEXT
- `Amount Value#40003702:18`: TEXT
- `Type`: VARIANT (Transaction, Order)

---

### Activity List

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003598:5936)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/activity-list/metadata.json`

**Available Properties:**
- `State`: VARIANT (Default, Empty)

---

### GhostFilter

- **Figma**: [View in Figma](https://www.figma.com/file/undefined?node-id=40003664:7838)
- **Variants**: 2
- **Properties**: 1
- **File**: `components/ghostfilter/metadata.json`

**Available Properties:**
- `State`: VARIANT (Active, Disabled)


## 🔄 Updates

This export includes:
- **409** new variables
- **0** updated variables
- **13** new components
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
