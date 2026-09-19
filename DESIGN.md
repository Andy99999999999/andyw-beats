---
name: Obsidian Crimson
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1e'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#e6bdbc'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#ad8887'
  outline-variant: '#5d3f3f'
  surface-tint: '#ffb3b2'
  primary: '#ffb3b2'
  on-primary: '#680014'
  primary-container: '#e51e3e'
  on-primary-container: '#fffeff'
  inverse-primary: '#bf002d'
  secondary: '#ffb3b3'
  on-secondary: '#680015'
  secondary-container: '#df0138'
  on-secondary-container: '#fff1f0'
  tertiary: '#ffb3b3'
  on-tertiary: '#61101a'
  tertiary-container: '#bc555a'
  on-tertiary-container: '#fffeff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b2'
  on-primary-fixed: '#410009'
  on-primary-fixed-variant: '#920020'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ffb3b3'
  on-secondary-fixed: '#400009'
  on-secondary-fixed-variant: '#920021'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#ffb3b3'
  on-tertiary-fixed: '#400009'
  on-tertiary-fixed-variant: '#80272e'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 1.75rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system channels the focused, high-stakes atmosphere of a 2:00 AM underground audio mastering suite. Designed specifically for elite producers, artists, and sound engineers, the aesthetic rejects the over-saturated chaos of generic gaming RGB and neon cyberpunk tropes in favor of an intimidating, surgically precise, high-contrast dark environment. 

The mood is tactile, predatory, and uncompromisingly professional. Interfaces should feel weighted like rack-mounted analog hardware, with razor-thin hairline boundaries, subtle radial crimson luminescence spilling behind dark matte finishes, and glowing red metering reminiscent of vacuum tubes and studio peak limiters. Every element projects raw sonic power refined by clinical acoustic discipline.

## Colors
The palette is built on strict tiers of absolute void and controlled thermal radiation:

- **Base Void & Surfaces**: The fundamental backdrop is rooted in `#08080a` and `#0d0d11`, generating unmatched contrast. Elevated surfaces shift gently into deep charcoal `#141418` and `#1a1a20` to prevent visual fatigue while maintaining pitch-black depth.
- **Crimson Accents**: `#e51e3e` serves as the primary visual driver for interactive elements, live audio playback, and primary actions. `#ff2a4b` operates exclusively for high-heat peak meters, live audio cursors, and active focus highlights. `#590915` provides deep-recessed shadow tinting and submerged backplates.
- **Typography & Content**: Pure white (`#ffffff`) is reserved strictly for track titles, key metrics, and high-impact values. Body text uses an off-white titanium `#d4d4d8`, while secondary metadata (BPM, Key, Stems) relies on muted ash `#71717a`.
- **Atmosphere**: Radial atmospheric glows use wide-spread gradients from `rgba(229, 30, 62, 0.08)` to `transparent` across empty canvas zones to emulate studio acoustic panel backlighting without obstructing content clarity.

## Typography
The typographic hierarchy merges industrial technical precision with brutal editorial authority:

- **Space Grotesk** commands headlines and titles with aggressive geometric cuts and authoritative tracking. It should always be set with tight line heights and negative letter-spacing for large sizes to deliver an upfront, punchy presence.
- **Hanken Grotesk** serves as the neutral workhorse for descriptions, licensing agreements, and long-form metadata. It provides invisible, razor-sharp clarity that recedes against deep dark backgrounds.
- **JetBrains Mono** handles all transactional, technical, and audio telemetry—including BPM, musical scale keys (e.g., `C# MINOR`), sample rates, duration timestamps, price values, and stem count tags. All mono labels should be uppercase to mimic studio hardware readouts.

## Layout & Spacing
The layout system enforces a structured, density-conscious architecture inspired by audio workstation interfaces (DAWs) and physical console routing strips:

- **Desktop (1280px+)**: A 12-column grid utilizing `gutter-desktop` (1.75rem / 28px) and minimum horizontal canvas margins of 3.5rem (56px). Global audio transport and real-time waveform scrubbers remain locked to viewport edges with zero lateral padding.
- **Tablet (768px - 1279px)**: An 8-column layout with 1.25rem (20px) gutters. Complex stem matrices reflow into vertically stacked modular blocks.
- **Mobile (320px - 767px)**: A 4-column layout utilizing tight 1rem (16px) margins. Beat browsing tables collapse into single-column track cards with simplified scrubbing scrubbars.
- **Spatial Cadence**: Spacing tokens follow an uncompromising base-4 dynamic rhythm. Components prioritize tight internal grouping (`space-xs` to `space-sm` for audio metrics) and broad atmospheric voids (`space-xl`) between catalog modules to create breathing room amidst intense, dark contrast.

## Elevation & Depth
Elevation is rendered strictly through tonal stratification and precise photon emission—traditional diffuse drop shadows are forbidden.

1. **Recessed / Void Level (z-0)**: Canvas background `#08080a`. Unlit, non-interactive foundation.
2. **Structural Layer (z-1)**: Audio tracks, catalog containers, and mixer racks at `#0d0d11`, framed by an ultra-fine border (`1px solid rgba(255, 255, 255, 0.04)`).
3. **Elevated Units (z-2)**: Interactive cards, beat rows, and popovers at `#141418`. Features a dual border structure: an inner perimeter of `1px solid rgba(255, 255, 255, 0.08)` and an exterior atmospheric glow under interaction.
4. **Thermal Active State (Interactive Focus / Playback)**: Active components cast a controlled, sinister glow:
   - Outer glow: `box-shadow: 0 0 15px -3px rgba(229, 30, 62, 0.35), inset 0 0 1px 1px rgba(229, 30, 62, 0.4)`
   - Subtle perimeter halo: `box-shadow: 0 8px 32px -4px rgba(229, 30, 62, 0.2)`
5. **Backdrop Lighting**: Major hero modules rest on top of ambient radial gradients: `radial-gradient(circle at 50% 0%, rgba(229, 30, 62, 0.12) 0%, transparent 65%)`, simulating diffused acoustic red lighting on studio baffling.

## Shapes
The design system leverages a compact, razor-sharp architectural geometry (Soft / Level 1). Buttons, cards, and input slots utilize `0.25rem` (4px) corner radiuses, echoing heavy-duty industrial audio controllers, machined anodized aluminum chassis, and audio rack gear. 

Pill shapes and round bubbles are strictly prohibited, with the sole exception of waveform scrubber playheads and master volume knobs. Micro-badges (tags for BPM, Key, and explicit tags) use sharp 2px chamfers or strict 2px radiuses to preserve an engineered, non-frivolous instrument look.

## Components

### Buttons
- **Primary Action (e.g., "Buy License", "Instant Checkout")**: Solid `#e51e3e` core with high-contrast `#ffffff` bold typography. On hover, background shifts to `#ff2a4b` with a focused peripheral aura (`box-shadow: 0 0 20px -2px rgba(229, 30, 62, 0.55)`).
- **Secondary / Studio Mode**: Deep matte black `#0d0d11` surface with a crisp border (`1px solid rgba(229, 30, 62, 0.5)`), off-white text, and an ambient red interior tint on hover (`box-shadow: 0 0 12px -2px rgba(229, 30, 62, 0.25)`).
- **Icon Buttons (Play / Pause / Mute)**: 36px or 44px square blocks with 4px radiuses. The active play button illuminates in `#e51e3e` with an unyielding red halo.

### Interactive Waveform Display
- Unplayed state: Dense micro-bars rendered in low-opacity gunmetal `#27272a`.
- Played/Active state: High-energy glowing `#e51e3e` bars with peak transients highlighted in `#ff2a4b`.
- Scrubber head: Razor-thin 1.5px vertical line in pure white (`#ffffff`) casting a continuous vertical 4px red shadow blur down the center of the track.

### Cards & Track Strips
- **Catalog Card**: Charcoal `#141418` base with a hairline `1px solid rgba(255, 255, 255, 0.05)` rim. On hover, the rim transforms into `rgba(229, 30, 62, 0.6)` with a delayed transition back-halo (`box-shadow: 0 12px 28px -6px rgba(0, 0, 0, 0.8), 0 0 15px -3px rgba(229, 30, 62, 0.35)`).
- **Track List Row**: Slim alternating rows (`#0d0d11` and `#101014`) equipped with left-edge indicator strips that ignite into a 3px vertical crimson bar when active or queued.

### Form Inputs & Knobs
- **Text & Search Fields**: Deep pitch black `#08080a` recessed fields with `1px solid rgba(255, 255, 255, 0.1)` borders. Upon focus, borders ignite to `#e51e3e` accompanied by an immediate `0 0 8px rgba(229, 30, 62, 0.3)` glow. Placeholder text is muted `#52525b`.
- **Checkboxes & Toggles**: Custom square-box toggles. Checked states fill with `#e51e3e`, centered with a crisp black glyph, completely free of playful curves.

### Chips & Licensing Badges
- Constructed with `JetBrains Mono` at `label-md`. Background in `#141418`, text in titanium `#d4d4d8`, framed by a dark ruby border `1px solid rgba(229, 30, 62, 0.2)`. Active or exclusive tags (e.g., `EXCLUSIVE SOLD`, `STEMS INCLUDED`) feature a solid `rgba(229, 30, 62, 0.15)` fill with `#ff2a4b` text.

### Master Audio Dock (Persistent Footer)
- A full-bleed horizontal chassis anchored at the screen bottom in `#0d0d11` with an elevated hairline top-border glowing in `rgba(229, 30, 62, 0.3)`. Houses global track timing, stereo peak VU meters operating from `#590915` (floor) to `#ff2a4b` (clipping limit), and quick-licensing checkout drawers.