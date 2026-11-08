# Themes

Keep application colors, typography, spacing, and control styles centralized. Prefer semantic tokens such as `Surface`, `TextPrimary`, `Accent`, and `BorderSubtle` over hard-coded colors in individual views.

## Guidance
- Define light and dark palettes from the same semantic token set.
- Keep shared styles in resource dictionaries and merge them deliberately.
- Use theme variants for component states, not duplicated view-specific styling.
- Verify contrast, focus visibility, disabled states, and high-DPI behavior.
- Avoid global implicit styles when they unexpectedly change third-party controls.

## Review
A view should communicate intent through semantic styles. A theme change should not require editing every screen.
