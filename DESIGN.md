---
name: Cyber Slate Minimalist
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#89ceff'
  on-secondary: '#00344d'
  secondary-container: '#00a2e6'
  on-secondary-container: '#00344e'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#9699ff'
  on-tertiary-container: '#1d17b2'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system is tailored for an ambitious web developer learner portfolio. It communicates technical precision, relentless growth, curiosity, and high-standard craft. The aesthetic leans into modern developer-centric minimalism fused with sharp technical utility—inspired by modern IDEs, developer documentation hubs, and high-performance CLI tools. 

The visual language balances deep slate charcoal foundations with hyper-focused vibrant neon accents: vibrant emerald to signify execution, compilation, and life; electric blue to communicate depth, logic, and architecture. Surfaces are clean, matte, and structural rather than noisy or skeuomorphic, establishing an aura of competence, high clarity, and purposeful digital engineering.

## Colors

The system defaults to a deeply calibrated dark mode (`#0B0F17`) engineered to reduce eye strain and celebrate syntax highlighting, with full semantic parity in light mode.

- **Primary (`#10B981` Emerald)**: Represents active statuses, main CTA highlights, code commit activity, and successful validations.
- **Secondary (`#0EA5E9` Electric Sky/Blue)**: Used for interactive links, technology stack tags, and secondary focus states.
- **Tertiary (`#6366F1` Indigo)**: Applied sparingly for accents, git-branch motifs, and subtle gradient keylines.
- **Neutral (`#0B0F17` Cyber Slate Canvas)**: Built on cool slate tones ranging from `#0B0F17` (canvas base) to `#161E2E` (card surface), `#26334D` (subtle borders), and `#F8FAFC` (high-contrast text).

## Typography

The typographic hierarchy is divided strictly between human-readable editorial clarity and developer-authentic syntax.

`Inter` handles macro headlines and body layouts, configured with tight tracking (`letterSpacing: -0.02em` to `-0.03em`) on large scale titles to produce crisp, modern tech editorial rhythm. 

`JetBrains Mono` governs metadata, terminal logs, project metrics, commit hashes, navigation badges, and tags. This dual-font pairing immediately informs the visitor that the portfolio belongs to a serious, code-literate builder.

## Layout & Spacing

The layout is architected on a responsive 12-column grid with a maximum content container of `1200px` to maintain strict legibility across ultrawide monitors while avoiding excessive scan-lines.

- **Desktop (1024px+)**: 12 columns, 24px (`1.5rem`) gutters, 48px (`3rem`) margins. Sections breathe with generous vertical pacing (`space-2xl` / 64px).
- **Tablet (768px - 1023px)**: 8 columns, 20px gutters, 32px margins. Multi-column showcase cards compress to 2 columns.
- **Mobile (< 768px)**: 4 columns, 16px (`1rem`) gutters, 20px (`1.25rem`) margins. Cards and project grids reflow to single-column full-width stacks.

## Elevation & Depth

Visual hierarchy is maintained without heavy skeuomorphic drops. Instead, this system utilizes a combination of **tonal layering**, **micro-surface contrast**, and **subtle luminescence**:

1. **Base Layer (Canvas)**: `#0B0F17` (Deep Cyber Slate).
2. **Elevated Surfaces (Cards, Modals, Terminal Panels)**: `#131B2A` with a 1px uniform structural border (`rgba(255, 255, 255, 0.08)` or `#1E293B`).
3. **Hover & Active States**: Surfaces shift to `#1A2438` with an accent perimeter highlight (`rgba(16, 185, 129, 0.4)` emerald or `rgba(14, 165, 233, 0.4)` electric blue glow).
4. **Shadows**: Only subtle ambient falloffs are permitted: `0 8px 30px rgba(0, 0, 0, 0.45)`, maintaining crisp mechanical definition rather than muddy blur.

## Shapes

The design system embraces a **Soft / Technical** shape language (`roundedness: 1`). 

Interactive buttons, inputs, badge tags, and cards adopt sharp yet refined 4px (`0.25rem`) to 8px (`0.5rem`) radiuses. Pill shapes are intentionally avoided for structural UI elements to preserve the disciplined, command-line IDE aesthetic. Only live status pings and commit dots use circular geometries (`rounded-full`).

## Components

### Buttons
- **Primary Action**: Emerald background (`#10B981`), dark slate text (`#0B0F17`), weight 600. On hover: subtle emerald box-glow and scale transition.
- **Secondary Action**: Translucent dark surface (`rgba(255, 255, 255, 0.04)`), 1px slate border (`#334155`), white text. On hover: border switches to electric blue (`#0EA5E9`).
- **Icon / Code Buttons**: Monospaced font, flat background, square aspect ratio with embedded SVG icons.

### Project & Case Study Cards
- Built with a 1px border (`rgba(255, 255, 255, 0.08)`), dark background (`#111827`).
- Includes a code-themed header (e.g. `fardan/ecommerce-engine:main`) rendered in `label-code` typography.
- Interactive hover lifts the card by 2px and applies an emerald or electric blue border transition.

### Chips & Badges
- Used for tech stack labels (e.g., `TypeScript`, `Next.js`, `TailwindCSS`).
- Styled with `JetBrains Mono`, `12px`, padding `4px 10px`, slight slate background (`#1E293B`), and crisp low-opacity accent borders.

### Input Fields & Terminal Inputs
- Background: `#0B0F17`, border: `#334155`, text: `#F8FAFC`.
- Focus ring: `2px solid #10B981` with zero offset to keep the mechanical terminal feel.
- Placeholder text in subdued `#64748B`.

### Checkboxes & Radio Controls
- Geometric square with 2px radius.
- Checked state fills with `#10B981` displaying a high-contrast dark checkmark.

### Additional Developer Components
- **Code Block Sandbox**: A mock terminal window featuring three macOS/Linux status dots (gray/subtle), copy-to-clipboard trigger, and syntax highlighting.
- **Learning Roadmap / Timeline Tracker**: A vertical rail with pulsating emerald nodes indicating ongoing learning topics vs completed modules.