# Behaviors and Interactions

Use interaction behaviors for reusable view-level interactions, while keeping business rules in the ViewModel or application layer.

## Guidelines
- Prefer the project's `Xaml.Interaction.Behaviors` conventions for reusable UI interactions.
- Keep event-to-command wiring explicit and testable.
- Do not hide domain logic in code-behind or converters.
- Dispose subscriptions and detach handlers when controls leave the visual tree.
- Guard against duplicate event registration and re-entrant commands.

Converters should remain small, deterministic presentation adapters. If logic requires branching, state, or I/O, move it into a dedicated service or ViewModel.
