# Frontend Mentor - Four card feature section solution

This is a clean, responsive, and modern solution to the Four card feature section challenge on Frontend Mentor.

## Links

- **Solution URL:** [https://github.com/veon321/Four-card-feature-section](https://github.com/veon321/Four-card-feature-section)
- **Live Site URL:** [https://veon321.github.io/Four-card-feature-section/](https://veon321.github.io/Four-card-feature-section/)

## Built with

- **Semantic HTML5 markup** (including `<main>` wrapper, structural `<header>`, and isolated modular card components)
- **CSS Custom Properties (Variables)** for strict adherence to the design system's color scheme and unified typography handling
- **Flexbox layout** for multidirectional alignment (main container stacking, inner card asset distribution, and vertical column grouping)
- **Modern CSS Math Functions (`clamp()`)** for completely fluid heading typography and responsive viewport adaptations
- **Google Fonts** (Poppins)

## Features

- **Asymmetric Multi-Column Flexbox Layout:** Accomplishes the distinctive "staircase" cross-formation layout using pure Flexbox logic. By isolating the two central blocks (_Team Builder_ and _Karma_) into a nested vertical flex column, the outer cards (_Supervisor_ and _Calculator_) are independently balanced on the cross-axis via `align-self: center`.
- **Fluid Gridless Responsiveness:** Avoids strict grid line setups, utilizing a smart breakdown mechanism. On medium devices, the system automatically transitions into a balanced two-column block, before completely normalizing into an inline vertical stack for small mobile screens.
- **Precision Image Pushing:** Leverages a flex directional column flow inside each card component, utilizing `margin-top: auto` on the asset container to anchor the functional icons perfectly into the lower-right corner regardless of dynamic text length variances.
- **Asymmetric Brand Accents:** Features clean, isolated borders using variables directly from the `:root` design palette (`border-top: 4px solid`) applied strictly to individual classes, keeping component behavior decoupled from layout definitions.
- **Screen Centering & Overflow Security:** Utilizes `min-height: 100vh` on the body tag for desktop presentation, paired with fluid `padding` and an mobile alignment pivot (`align-items: flex-start`), ensuring content never clips or overflows the top viewport boundary on ultra-compact mobile layouts.
