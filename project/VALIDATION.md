# Validation

- 15 page routes, including 11 distinct screens and 4 descriptive aliases.
- Every route contains index.html and style.css.
- Shared css/global.css and local font/image/icon assets verified.
- 431 local HTML references checked; no missing files or anchors.
- CSS parsed successfully; no CSS Grid, float, absolute/fixed/sticky positioning, table layouts, or !important declarations.
- No script tags, event handlers, inline CSS, external CSS frameworks, or JavaScript files.
- All 11 distinct screens checked in the browser at 1280px, 1024px, and 360px. All 15 routes checked at 320px. No horizontal document overflow or broken image loads.
- Native step-out duration selection and confirmation disclosure verified. Empty sign-in form rejected by native validation. Identity fields are excluded from form submission.
- Sample waiting-pass PDF rendered and visually checked.

Pixel-for-pixel parity is not certified. See README.md for the Figma connector quota limitation and static functionality boundaries.
