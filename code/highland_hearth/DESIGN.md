---
name: Highland & Hearth
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#434844'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#737874'
  outline-variant: '#c3c8c2'
  surface-tint: '#516257'
  primary: '#06160e'
  on-primary: '#ffffff'
  primary-container: '#1b2b22'
  on-primary-container: '#819387'
  inverse-primary: '#b8cbbe'
  secondary: '#81542b'
  on-secondary: '#ffffff'
  secondary-container: '#ffc390'
  on-secondary-container: '#794e26'
  tertiary: '#1f0f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#3c2100'
  on-tertiary-container: '#c47f2a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e7d9'
  primary-fixed-dim: '#b8cbbe'
  on-primary-fixed: '#0f1f16'
  on-primary-fixed-variant: '#3a4b40'
  secondary-fixed: '#ffdcc1'
  secondary-fixed-dim: '#f5bb89'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#653d16'
  tertiary-fixed: '#ffdcbc'
  tertiary-fixed-dim: '#ffb86a'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#683d00'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-edge: 40px
  section-gap: 120px
---

## Brand & Style

This design system targets a discerning outdoor audience, blending the rugged authenticity of the wilderness with the polished aesthetic of a high-end editorial publication. The brand personality is authoritative yet welcoming—positioning the influencer as both a master of the craft and a sophisticated storyteller.

The design style is **Modern Editorial with Tactile accents**. It leverages the "New Minimalist" approach: generous whitespace and structured layouts that allow high-resolution photography of landscapes and gear to drive the emotional narrative. By mixing sharp, high-contrast serif headers with functional sans-serif utility, the UI evokes a sense of timeless tradition meeting modern technical excellence. The interface should feel like a premium coffee-table book: intentional, grounded, and expensive.

## Colors

The palette is rooted in the natural world, using deep, desaturated tones to establish authority and warmth.

*   **Primary (Deep Forest):** A rich, near-black green used for core branding, primary buttons, and immersive backgrounds. It represents the depth of the woods.
*   **Secondary (Earthy Brown):** A mid-tone saddle brown used for supporting elements, borders, and hover states, providing a leather-like warmth.
*   **Tertiary (Warm Ochre):** A vibrant accent used sparingly for calls-to-action, badges, and highlights. It mimics the glow of a sunset or a campfire.
*   **Neutral (Dark Charcoal):** Used for primary text on light backgrounds to avoid the harshness of pure black, maintaining a soft, premium feel.

The system utilizes "Paper White" (#F9F8F6) for main backgrounds to provide a slight warmth compared to sterile digital white, paired with "Obsidian" (#121212) for high-contrast dark sections.

## Typography

The typography strategy relies on the tension between the classic and the contemporary. 

**Noto Serif** is the voice of the brand. It is used for all major headlines and storytelling moments. High-contrast strokes provide an elegant, literary quality.

**Manrope** serves as the workhorse for body copy. Its modern, geometric construction ensures maximum legibility across all devices, even in long-form gear reviews or expedition logs.

**Work Sans** is reserved for metadata, labels, and navigation. Used primarily in uppercase with increased letter-spacing, it provides a clean, "technical gear" feel that balances the softer serif headlines.

## Layout & Spacing

The layout follows a **Strict Editorial Grid**. It uses a 12-column system for desktop with generous gutters to prevent the UI from feeling cluttered.

Spacing is used to create "breathing room," mimicking the vastness of the outdoors. Sections should be separated by significant vertical gaps (120px+) to allow the eye to rest and focus on one story at a time. Content is generally centered within a fixed-width container to maintain readability, while imagery often breaks the grid, spanning the full width of the viewport to create an immersive experience.

## Elevation & Depth

To maintain a grounded, tactile feel, this design system avoids heavy shadows and floating effects. Instead, depth is achieved through:

*   **Tonal Layering:** Using different background shades (e.g., a Forest Green section following a Paper White section) to create a sense of physical transition.
*   **Low-Contrast Outlines:** Elements like cards or input fields use subtle, 1px borders in desaturated brown or grey (#D1CDC7) rather than shadows.
*   **Micro-Depth:** Small, 2px "press" effects on active buttons and very soft, ambient shadows (4% opacity) for high-importance overlays to make them feel like they are resting on a surface rather than hovering in space.

## Shapes

The shape language is primarily **Soft (0.25rem)**. While a hunting brand might traditionally use sharp edges, the subtle rounding adds a "refined" and "modern" touch that distinguishes it from basic tactical brands. 

Buttons and cards use a slight corner radius to feel approachable and high-end. Interactive icons should be contained within circles or squares with the same soft-radius treatment. Overlays and decorative elements may occasionally use 0px corners to reinforce a sense of architectural structure.

## Components

### Buttons
Primary buttons are solid Deep Forest with white text, utilizing an "Editorial Arrow" icon on hover. Secondary buttons use a transparent background with a secondary brown border. All buttons have a transition that slightly deepens the background color.

### Cards
Cards for blog posts or gear reviews use a "contained bleed" layout: the image sits at the top with no padding, while the text below is inset with generous padding. Borders are thin and light, keeping the focus on the photography.

### Inputs & Forms
Input fields use a "minimalist line" or a very light-filled background with no heavy borders. Labels use the `label-caps` typography style, positioned strictly above the input for a clean, organized look.

### Chips & Badges
Used for categories like "Expeditions" or "Gear," these are small, pill-shaped elements using the Tertiary Ochre color with high-contrast text. They should feel like a premium tag on a piece of equipment.

### Signature Component: The "Field Note"
A unique card style with a paper texture background and a subtle serif italic font, used for pull-quotes, quick tips, or personal notes from the influencer. It should feel like a scrap of paper from a field journal.