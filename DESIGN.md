---
name: Compassionate Dignity
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#43474d'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607e'
  primary: '#00152b'
  on-primary: '#ffffff'
  primary-container: '#102a45'
  on-primary-container: '#7a92b2'
  inverse-primary: '#b0c8eb'
  secondary: '#0051d3'
  on-secondary: '#ffffff'
  secondary-container: '#346ced'
  on-secondary-container: '#fefcff'
  tertiary: '#09161e'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e2a34'
  on-tertiary-container: '#85919d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b0c8eb'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#314865'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b3c5ff'
  on-secondary-fixed: '#00174a'
  on-secondary-fixed-variant: '#003ea6'
  tertiary-fixed: '#d7e4f1'
  tertiary-fixed-dim: '#bbc8d5'
  on-tertiary-fixed: '#111d26'
  on-tertiary-fixed-variant: '#3c4853'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
  surface-canvas: '#F4F8FC'
  surface-card: '#FFFFFF'
  border-subtle: '#CDE1F4'
  accent-warm: '#F59E0B'
  status-positive: '#166534'
typography:
  display-lg:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Public Sans
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a human, deeply authentic, and institutionally credible visual identity for an orphanage and community initiative. The aesthetic blends civic reliability with heartfelt compassion. It departs from glossy tech motifs, playful juvenile tropes, or generic charity aesthetics, anchoring itself instead in restrained institutional dignity.

The design movement is **Modern Civic Editorial**: structured, architectural layouts balanced with large-format documentary photography. Interfaces must feel rooted, transparent, and respectful. We avoid superficial micro-animations, decorative gradients, playful floating blobs, or emojis. Every element serves clarity, impact reporting, and dignified human storytelling.

## Colors

The color palette establishes deliberate hierarchy through high-contrast naval depth and crisp atmospheric blues:

- **Primary (`#102A45`)**: Deep Navy anchors the brand architecture. It provides commanding presence across header navigation, section hero blocks, institutional footers, and primary typographic weight.
- **Secondary (`#185ADB`)**: Sapphire drives action. Used exclusively for actionable affordances: donation triggers, text links, active tabs, and primary controls.
- **Tertiary (`#DCE9F6`)**: Powder Blue serves as an environmental tint for sub-panels, structural dividers, and secondary badge fills.
- **Neutral (`#111827`)**: Deep Charcoal guarantees optimal readability across body copy, ensuring an accessible contrast ratio against white and light tinted backgrounds.
- **Named Colors**:
  - `surface-canvas` (`#F4F8FC`): A soft Ice Blue tint that provides optical relief without feeling starkly cold.
  - `surface-card` (`#FFFFFF`): Pure White used for elevated surfaces and cards to cut cleanly against the Ice Blue ground.
  - `border-subtle` (`#CDE1F4`): A refined structural perimeter color for form inputs and card perimeters.
  - `accent-warm` (`#F59E0B`): Used sparingly for high-priority urgent appeals or highlighted financial metrics.
  - `status-positive` (`#166534`): Used for verification badges, transparent governance markers, and audit confirmations.

## Typography

The type scale relies exclusively on **Public Sans**, selected for its civic clarity, institutional legibility, and no-nonsense neutral geometry. 

- **Display & Headlines**: Bold, structural weights (`600` to `700`) with tight tracking impart authority and clarity on annual impact metrics and program titles.
- **Body**: Regular (`400`) weight configured at a comfortable 150% line height ratio to guarantee effortless reading across program narratives, child welfare reports, and case histories.
- **Labels & Metas**: Structured uppercase or medium-weighted small labels provide clean categorization for sponsorship tiers, dates, and regulatory accreditation tags.

## Layout & Spacing

The layout model is governed by a responsive **12-column fluid grid** system bounded at a maximum container width of `1280px`.

- **Desktop (1024px and up)**: 12 columns with a `1.5rem` (`24px`) gutter and `2.5rem` (`40px`) outer page margin. Sections transition with generous vertical breathing room (`space-xl` and above) to evoke quiet dignity and calm clarity.
- **Tablet (768px - 1023px)**: 8 columns with `1.5rem` gutters and `1.5rem` outer margins. Two-column cards convert cleanly into full widths or two-up modules.
- **Mobile (under 768px)**: 4 columns with a `1rem` (`16px`) gutter and `1rem` (`16px`) outer margins. Editorial side-by-side modules collapse strictly into vertical rhythm stacks.

## Elevation & Depth

Visual hierarchy is maintained through **crisp low-contrast outlines and tonal surface stratification** rather than heavy drop shadows.

- **Surface Layers**: The foundation is canvas tint `surface-canvas` (`#F4F8FC`). Elevated units (story cards, donation modules, transparency sheets) sit on `surface-card` (`#FFFFFF`).
- **Outlines**: Structural definition uses an unyielding, crisp 1px border colored with `border-subtle` (`#CDE1F4`).
- **Shadows**: Shadows are strictly restrained. When required to indicate interactive hover or modal popovers, use a single subtle, non-diffused offset: `0 2px 4px rgba(16, 42, 69, 0.06), 0 1px 2px rgba(16, 42, 69, 0.04)`. Blur radius never exceeds 8px; colored glows or dramatic blurs are forbidden.

## Shapes

The shape system is strictly **Soft (Level 1)**, bounded between `4px` and `8px` (`0.25rem` to `0.5rem`). 

- **Never Pill-Shaped**: Full border-radii (`9999px`) are completely prohibited. Buttons, input fields, badges, and avatars utilize disciplined rectangular frames.
- **Standard Radius**: Core interactive components (buttons, input boxes, list items) use a `4px` corner radius.
- **Card & Modal Radius**: Larger structural surfaces (cards, disclosure panes, dialogs) carry a maximum radius of `8px`.
- **Media**: Photography adheres strictly to crisp `4px` to `8px` corners or remains completely unrounded when flush with edge containers.

## Components

### Buttons
- **Primary**: Solid Sapphire (`#185ADB`) background, white text, 4px border-radius, font weight `600`. Hover shifts to `#1346aa`.
- **Secondary**: Crisp 1px border (`#102A45`), transparent background, Deep Navy text (`#102A45`). Hover adopts `#F4F8FC`.
- **Tertiary / Link**: Sapphire text, no border, persistent or hover underline with 2px underline offset.
- **Padding**: Standard size is `10px 20px` (`0.625rem 1.25rem`); compact size is `8px 16px`.

### Cards & Data Panels
- Pure White background (`#FFFFFF`) with a continuous 1px outline of `#CDE1F4`.
- Padding of `1.5rem` (`24px`).
- Photo headers within cards must display zero gap at the top and flush borders, utilizing authentic documentary imagery.

### Input Fields & Controls
- **Form Inputs**: White background, 1px border in `#CDE1F4`, 4px border-radius, `12px 16px` padding. Focus state features a sharp 1px ring in Sapphire (`#185ADB`) without blurry outer glow rings.
- **Checkboxes & Radios**: 16px square (or circle for radio) with a 1px `#102A45` border. Checked state fills with `#185ADB` featuring a white geometric checkmark.

### Chips & Badges
- Strictly rectangular with a 4px corner radius.
- Standard metadata badge: `#DCE9F6` background with `#102A45` text, tracking `0.02em`, 12px font size, padding `4px 8px`.

### Lists & Tables
- Divided with thin 1px horizontal rules in `#CDE1F4`.
- Alternating row fills are prohibited; clarity is maintained through whitespace (`16px` vertical cell padding) and distinct type hierarchy.

### Iconography
- Clean, open, 1.5px monoline stroke icons in matching text/brand colors.
- Stylized 3D graphics, heavy fills, emojis, and abstract AI illustrations are strictly prohibited.