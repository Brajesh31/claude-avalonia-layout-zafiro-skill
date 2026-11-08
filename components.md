# Reusable Components

Create generic components only when they have a stable, repeated responsibility.

## Component design
- Define a small public API with typed properties and clear defaults.
- Keep visual structure predictable and expose only necessary customization points.
- Avoid nesting generic components to recreate a one-off layout.
- Prefer composition over a large component with many boolean switches.
- Document focus behavior, sizing constraints, and theme resources.

## When not to extract
Do not create a reusable component for a single trivial layout unless it establishes an important design-system primitive.
