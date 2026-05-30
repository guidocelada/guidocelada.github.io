# Design

## Theme

Mobile-first informational healthcare site for a local clinical laboratory. The first viewport should feel closer to a practical patient assistant than to a marketing landing page: address, hours, WhatsApp and services are visible quickly.

## Visual Direction

Use the provided mobile mockups as direction, especially the version with a yellow address panel, real facade photography, "Como podemos ayudarte?" action list, quick contact buttons and dark footer. Refine it with stronger accessibility, calmer density and real laboratory assets.

## Color

- Ink: `oklch(18% 0.02 245)`
- Muted ink: `oklch(42% 0.02 245)`
- Paper: `oklch(99% 0.004 95)`
- Soft surface: `oklch(97% 0.008 95)`
- Line: `oklch(88% 0.012 95)`
- Celada yellow: `oklch(84% 0.18 88)`
- Yellow soft: `oklch(95% 0.075 88)`
- WhatsApp green: `oklch(57% 0.18 150)`

Yellow is a strong accent for the hero address panel, CTAs, icons and trust indicators. It should not become the entire page background.

## Typography

Use Lato for body readability and accessibility. Use Figtree for headings and primary navigation to keep the site clean, warm and professional, with normal numerals. Body text starts above 16px, with generous line height. Do not use negative letter spacing.

## Layout

Use real photos from `public/assets/images/photos/`. Mobile stacks content in patient-task order. Desktop can use two-column bands, but the same information hierarchy must remain: address, hours, WhatsApp, domicile, results and insurance.

## Components

- Sticky header with logo, short navigation and WhatsApp action.
- Hero address panel paired with real facade photography.
- Large action list for common patient intents.
- Common studies grid.
- Trust indicators and Google Maps review prompt.
- Native `details` FAQ.
- Floating WhatsApp button.
- Dark footer with concise local trust copy.
