---
name: Atelier Littéraire
colors:
  surface: '#fcf9f2'
  surface-dim: '#dcdad3'
  surface-bright: '#fcf9f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ec'
  surface-container: '#f0eee7'
  surface-container-high: '#ebe8e1'
  surface-container-highest: '#e5e2db'
  on-surface: '#1c1c18'
  on-surface-variant: '#41484b'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f0ea'
  outline: '#71787c'
  outline-variant: '#c1c7cc'
  surface-tint: '#376476'
  primary: '#003747'
  on-primary: '#ffffff'
  primary-container: '#1f4e5f'
  on-primary-container: '#92bed2'
  inverse-primary: '#a0cde1'
  secondary: '#9b4500'
  on-secondary: '#ffffff'
  secondary-container: '#fe8e46'
  on-secondary-container: '#6b2e00'
  tertiary: '#143642'
  on-tertiary: '#ffffff'
  tertiary-container: '#2d4d5a'
  on-tertiary-container: '#9cbdcc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bce9fe'
  primary-fixed-dim: '#a0cde1'
  on-primary-fixed: '#001f29'
  on-primary-fixed-variant: '#1d4c5d'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68d'
  on-secondary-fixed: '#331200'
  on-secondary-fixed-variant: '#763300'
  tertiary-fixed: '#c6e8f7'
  tertiary-fixed-dim: '#aaccdb'
  on-tertiary-fixed: '#001f29'
  on-tertiary-fixed-variant: '#2b4b58'
  background: '#fcf9f2'
  on-background: '#1c1c18'
  surface-variant: '#e5e2db'
  cream-page: '#F7F3E8'
  cream-surface: '#FAF7F0'
  terracotta-hover: '#8E4000'
  border-tone: '#DCD4C0'
  white-pure: '#FFFFFF'
typography:
  headline-xl:
    fontFamily: Lora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lora
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Lora
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.025em
  headline-md:
    fontFamily: Lora
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Lora
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 26px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Work Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 1.5rem
  margin: 1rem
  margin-sm: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system translates the intimate, cultured atmosphere of an independent bookstore in Nantes into an accessible, tactile digital sanctuary. Designed for literary enthusiasts, neighborhood book buyers, and readers seeking personalized human recommendations ("MatchPassants"), the aesthetic couples the tactile weight of artisan paper with the clarity of contemporary editorial design.

The design movement blends **Tactile Editorial** with **Accessible Functionalism**:
- Natural, unbleached paper textures and warm cream canvases replace sterile pure whites.
- Visual warmth is driven by architectural Nantes terracotta and deep oceanic petrol inks.
- Every interface choice is anchored in strict accessibility principles: minimum interactive touch bounds of 44×44px, unambiguous microcopy, robust color contrast exceeding WCAG AA standards, and semantic text tags alongside every icon.
- Interactive feedback mirrors physical handling: soft deckle-edge borders, layered fan cards inspired by hand-held book leaves, and responsive physical press states (`scale-95`).

## Colors

The palette reproduces physical print materials—ink, paper, and architectural terracotta.

### Palette Hierarchy & Roles
- **Primary (`#1F4E5F` — Deep Petrol)**: Serves as the primary dark tone, taking the role of text copy, title rendering, structural outlines, and principal branding elements. Conveys academic authority and readability without the harshness of pure black.
- **Secondary (`#A64B00` — Nantes Terracotta)**: Used selectively for warm accents, curated selections ("Coups de cœur"), actionable match triggers ("Trouver mon match"), active focus indicators, and category underline flourishes.
- **Tertiary (`#133541` — Abyssal Petrol)**: Deepened state for interactive hover shifts, media scrims, and anchoring header/footer accents.
- **Neutral (`#FAF7F0` — Light Cream / Ivory)**: Base container backdrop that softens glare, complemented by `#F7F3E8` for stacked cards and outer borders in `#DCD4C0`.

### Accessible Contrast & Opacity Token Rules
- **Text on Cream Surfaces**: `#1F4E5F` delivers a contrast ratio exceeding `9.2:1` on `#FAF7F0`, well above the WCAG AAA threshold of `7:1`.
- **Accent Action Elements**: White `#FFFFFF` against `#A64B00` maintains an accessible contrast ratio of `4.8:1` for buttons.
- **Muted Shades**: Never wash out vital text. Secondary metadata uses an opacity floor of at least 75% (`rgba(31, 78, 95, 0.75)`), yielding compliant `5.5:1` contrast.
- **Interactive State Accents**: Tinted selection highlight uses `#A64B00` with foreground `#FFFFFF`.

## Typography

The typography system pairs the literary grace of **Lora** with the utilitarian clarity of **Work Sans**.

### Roles & Composition
- **Editorial Headings (`Lora`)**: Communicates the heritage and literary voice of the bookshop. Headings 1 through 4 use generous line heights (`1.25` to `1.375`) and negative tracking on larger scales to ensure compact, book-jacket-like impact.
- **Interface & Text (`Work Sans`)**: The primary text size strictly conforms to the accessibility commitment of **16px** base. Line spacing is calibrated to `1.625` for relaxed, sustained reading comfort on light cream backgrounds.
- **Labels & Microcopy (`Work Sans`)**: Buttons, badges, tags, and category eyebrows leverage elevated weights (`600`, `700`) paired with open letter spacing (`0.05em` to `0.1em`) to maintain legibility in uppercase transformations.

## Layout & Spacing

The layout model emphasizes focused readability within an editorial container.

### Layout Model
- **Reading Enclosure**: A centered, mobile-first column capped at a maximum width of `28rem` (`448px`, `max-w-md`) on mobile, scaling up to standard content boundaries (`sm: 640px`, `lg: 1024px`) for catalog and bookshelf overviews.
- **Rhythm & Grid**: Content sections use a stacked column rhythm spaced by `space-lg` (`1.5rem`) and `space-xl` (`2rem`). Multicolumn sections (such as contact blocks or dual matchmaking splitters) switch from a single-column stack on mobile to a balanced 2-column grid at `640px` (`sm:` breakpoint).
- **Physical Touch Target Rule**: Regardless of visual padding, every interactive element—including links, buttons, hamburger icons, and book carousel chevrons—maintains an explicit bounding zone of at least **44×44px** (`min-h-[44px] min-w-[44px]`).

## Elevation & Depth

Visual hierarchy uses pigmented, physical paper elevation instead of synthetic neutral shadows.

### Elevation Tiers
- **Flat Ground**: The global page background uses `#FAF7F0` overlaid with a subtle paper grain: `radial-gradient(#1F4E5F 0.5px, transparent 0.5px)` with a scale of `24px 24px` at `3.5%` opacity.
- **Card Tier (`shadow-card`)**: Floating cards, section containers, and information panels rest with an organic tint: `0 4px 14px 0 rgba(31, 78, 95, 0.08)` coupled with an intentional `1px` or `2px` boundary line of `rgba(31, 78, 95, 0.15)`.
- **Book Shadow Tier (`shadow-book`)**: Elevated overlapping cards (e.g. hero recommendation overlap at `-mt-6`) produce stacked physical depth: `0 8px 24px -4px rgba(31, 78, 95, 0.18), 0 3px 6px -2px rgba(31, 78, 95, 0.08)`.
- **Translucent Navigation**: The top app bar applies `rgba(247, 243, 232, 0.95)` with `backdrop-blur-md` and a boundary border of `rgba(31, 78, 95, 0.15)`.
- **Paper Fan Depth**: Overlapping shelf and curated display cards use relative depth layering:
  - Outer cards: `z-10`, transformed with `rotate(±10deg) translateY(6px)`
  - Center hero card: `z-20`, transformed with `translateY(-8px)` and `shadow-book`

## Shapes

The design system uses a balanced corner radius (`roundedness: 2`, `8px` / `0.5rem` base) to reflect the bound edges of physical cloth-bound books.

### Corner Radius System
- **Structural Containers (`16px` / `rounded-2xl`)**: Surrounds major grouped areas, such as the hero framing canvas and the unified contact/location block.
- **Overlapping Floating Panels (`12px` / `rounded-xl`)**: Applied to internal feature cards, matching modules, and popover panels.
- **Functional Components (`8px` / `rounded-lg`)**: Applied to square brand marks, text inputs, textareas, and touch target tiles.
- **Pill Elements (`9999px` / `rounded-full`)**: Applied exclusively to primary discovery actions ("Trouvez", "Matchez"), recommendation badges, and floating carousel controllers.

## Components

### Buttons & Interactive Controls
- **Terracotta Action Buttons (Primary CTA)**:
  - Background: `#A64B00`, Text: `#FFFFFF` (`Work Sans 700`, `14px`, uppercase tracking `0.1em`).
  - Min-height: `44px`, horizontal padding: `1.25rem`. Roundedness: `rounded-lg` or `rounded-full`.
  - Hover: `#8E4000`, Active: `transform scale-95 transition-transform duration-150`. Focus: `2px` offset ring in `#A64B00`.
- **Petrol Secondary Buttons**:
  - Background: `#1F4E5F`, Text: `#FFFFFF`. Hover: `#133541`.
- **Ghost & Outlined Buttons**:
  - Border: `2px solid #1F4E5F`, Background: `transparent`, Text: `#1F4E5F`. Hover: `rgba(31, 78, 95, 0.05)`.
- **Dual Choice Splitter ("Vous savez ce que vous voulez ?")**:
  - Pill containers (`rounded-full`) with full `min-h-[44px]` touch targets. Left pill ("Trouvez") features a search magnifier icon accompanied by text; right pill ("Matchez") features heart glyphs accompanied by text.

### Chips & Badges
- **Curator's Tag ("Coup de Cœur" / "Librairie Indépendante")**:
  - Background: `rgba(247, 243, 232, 0.95)`, Border: `1px solid rgba(31, 78, 95, 0.20)`. Text: `#1F4E5F`, `11px`, `font-semibold`.
  - Always includes an explicit icon alongside the label (e.g. solid heart or open book).

### Form Inputs & Text Fields
- **Search & Contact Inputs**:
  - Background: `#FFFFFF`, Border: `1.5px solid rgba(31, 78, 95, 0.25)`, Radius: `8px`.
  - Height: `44px` minimum (`py-2.5 px-3.5`).
  - Text: `Work Sans 16px` in `#1F4E5F`. Placeholder: `rgba(31, 78, 95, 0.50)`.
  - Focus: Outline none, border `#A64B00`, `box-shadow: 0 0 0 3px rgba(166, 75, 0, 0.15)`.
  - Search fields always couple the input with a visible text label or accessible submit icon button.

### Cards & Book Displays
- **Curated Book Leaf Card**:
  - Surface: `#FAF7F0`, Border: `1px solid rgba(31, 78, 95, 0.15)`, Padding: `1.25rem`.
  - Features book jacket preview with descriptive alt text, bold serif title (`Lora 18px`), author name in `Work Sans 14px`, and price tag clearly visible.
- **Shelves / Carousel ("Nos Rayons")**:
  - Center card elevated with `shadow-book` and scale.
  - Directional chevron tap targets strictly adhere to `44x44px` with clear `aria-label="Rayon précédent"` / `aria-label="Rayon suivant"`.

### Contact & Opening Hours Panel
- **Human Connection Tile**:
  - Highlighting direct phone lines and street address for patrons seeking in-person advice.
  - Icons (phone, location marker, clock) are rendered at `20x20px` in `#1F4E5F` and must always be paired directly with explicit text labels.

### Accessibility Safeguards
- Non-text information (color) is never used as the sole conveyor of status.
- Every icon (magnifier, filter, arrow, phone) is backed by visible copy or screen-reader announcements.
- Transitions remain strictly within `150ms` using standard easing curves to protect motion-sensitive readers.