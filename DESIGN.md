---
name: Photon C.T.O.
colors:
  surface: '#131319'
  surface-dim: '#131319'
  surface-bright: '#393840'
  surface-container-lowest: '#0e0e14'
  surface-container-low: '#1b1b22'
  surface-container: '#1f1f26'
  surface-container-high: '#2a2930'
  surface-container-highest: '#35343b'
  on-surface: '#e4e1ea'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e4e1ea'
  inverse-on-surface: '#303037'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ffabef'
  on-secondary: '#5c0058'
  secondary-container: '#ff0df5'
  on-secondary-container: '#51004d'
  tertiary: '#faf3ff'
  on-tertiary: '#3c0090'
  tertiary-container: '#e1d2ff'
  on-tertiary-container: '#7213ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#ffd7f3'
  secondary-fixed-dim: '#ffabef'
  on-secondary-fixed: '#390036'
  on-secondary-fixed-variant: '#82007d'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d1bcff'
  on-tertiary-fixed: '#23005b'
  on-tertiary-fixed-variant: '#5700c9'
  background: '#131319'
  on-background: '#e4e1ea'
  surface-variant: '#35343b'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 88px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  cta-button:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
This design system captures the frenetic, high-velocity energy of the TON meme-coin ecosystem. The brand personality is aggressive, innovative, and unapologetically "Degen-forward," targeting a demographic that values speed, high-tech aesthetics, and community-led movements.

The visual style is a fusion of **Vaporwave Futurism** and **Low-Poly Brutalism**. It utilizes sharp, crystalline geometric shapes inspired by faceted low-poly art, combined with intense neon glows and glassmorphic overlays. The interface should feel like a high-end trading terminal crossed with a futuristic battle HUD, evoking an emotional response of urgency and "light-speed" momentum.

## Colors
The palette is rooted in a deep "Obsidian" neutral to ensure maximum contrast for the vibrant neon accents. 

- **Electric Cyan (Primary):** Used for primary actions, critical data points, and "Photon" energy effects.
- **Vibrant Magenta (Secondary):** Used for secondary CTAs and highlights to provide a classic vaporwave juxtaposition.
- **Deep Obsidian (Neutral):** The foundation of the UI, creating a void-like depth that allows light-emitting elements to pop.
- **Neon Purple (Tertiary):** Used for background gradients, low-poly shadows, and depth-defining accents.

Functional colors should leverage the Cyan for "Up/Buy" signals and a high-contrast Red-Orange for "Down/Sell" signals, though the primary focus remains on the "pumping" energy of the brand colors.

## Typography
The typography is designed to feel sharp, technical, and aggressive. 

- **Headlines:** Use **Space Grotesk**. Its geometric quirks and wide stance feel futuristic and high-tech. Use tight tracking on large displays to create a solid, impactful wall of text.
- **Body:** Use **Geist** for its extreme legibility and "developer-tool" precision. It maintains the tech-focused aesthetic without sacrificing readability during long scrolls.
- **Data/Labels:** Use **JetBrains Mono** for all numerical data, contract addresses, and technical labels to reinforce the "CTO" (Community Take Over/Chief Technology Officer) technical narrative.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop to maintain a tight, "dashboard" feel, transitioning to a fluid model for mobile.

- **Desktop:** 12-column grid with 24px gutters. Content is often contained within "modules" that mimic crystalline shards.
- **Rhythm:** Use a base 4px increment. Large sections should be separated by aggressive 120px+ vertical padding to allow the low-poly background textures to breathe.
- **Alignment:** Use asymmetrical layouts to evoke energy. For example, text blocks might be offset against floating 3D low-poly crystal assets.

## Elevation & Depth
Depth is not created through traditional shadows, but through **Light Emission and Layering**.

- **Backdrop Blurs:** Use heavy (32px+) backdrop blurs on surfaces to create a "frosted obsidian" glass effect.
- **Neon Underglows:** Instead of drop shadows, use `box-shadow` with high spread and low opacity using the Primary Cyan or Secondary Magenta colors to make elements appear as if they are floating on a bed of light.
- **Faceted Layers:** Use clipping masks or SVG backgrounds to create low-poly, diamond-like facets on container corners, giving them a physical, crystalline presence.

## Shapes
The shape language is strictly **Sharp (0px)** or highly angular. 

- **Hard Edges:** All primary containers and buttons should have 0px border-radius to maintain a "blades and crystals" aesthetic.
- **Clipped Corners:** For a more advanced "HUD" look, use CSS `clip-path` to create chamfered (beveled) corners on cards and buttons.
- **Lines:** Use 1px or 2px borders with linear gradients (Cyan to Transparent) to define edges without closing off shapes entirely.

## Components
- **Light-Speed Buttons:** Sharp-edged, uppercase text, with a continuous "scan-line" animation moving across the background. On hover, the button should trigger an intense outer glow (Primary Cyan).
- **Crystalline Cards:** Deep obsidian backgrounds (#0D0D1A) with 1px semi-transparent cyan borders. Incorporate a low-poly watermark pattern in the background at 5% opacity.
- **Status Chips:** Use JetBrains Mono. Success states should pulse with a Cyan glow; "Live" states should have a magenta "pumping" animation.
- **Input Fields:** Minimalist. Only a bottom border that glows brighter when focused. Placeholder text should use the Monospaced font.
- **Energy Progress Bars:** Used for "pumping" stats or liquidity goals. Use a multi-stop gradient (Purple -> Magenta -> Cyan) with a jittering animation to simulate high voltage.
- **Data Readouts:** Large numerical displays for market cap or holders should use the Primary Cyan color with a faint "flicker" entry animation.