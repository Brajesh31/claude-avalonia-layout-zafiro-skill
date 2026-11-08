# claude-avalonia-layout-zafiro-skill

A Claude Code skill for building clean, reusable Avalonia UI layouts with Zafiro.Avalonia patterns.

## Overview

This skill helps structure Avalonia views using semantic containers, shared styles, reusable components, and consistent icon and behavior patterns. It aims to reduce unnecessary XAML duplication while keeping layouts readable and maintainable.

## Main Capabilities

- Organize shared application themes.
- Select semantic layout containers.
- Reuse generic UI components.
- Apply consistent icon patterns.
- Implement XAML interaction behaviors.
- Reduce unnecessary converters and nested markup.
- Keep view layout consistent across the application.
- Review component composition and styling.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-avalonia-layout-zafiro-skill.git ~/.claude/skills/avalonia-layout-zafiro
```

## Usage

Invoke the skill when designing or refactoring Avalonia layouts:

```text
/avalonia-layout-zafiro
```

Provide the Avalonia version, Zafiro package version, target view, design requirements, and existing theme conventions.

## Reference Guide

| File | Focus |
|---|---|
| `themes.md` | Theme organization and shared styles |
| `containers.md` | Semantic containers and layout structure |
| `icons.md` | Icon extensions and configuration |
| `behaviors.md` | XAML interaction behaviors |
| `components.md` | Generic and reusable components |

## Recommended Workflow

1. Inspect the existing theme and shared styles.
2. Identify the semantic structure of the view.
3. Select suitable containers and components.
4. Reuse existing styles before adding new ones.
5. Keep XAML hierarchy shallow and readable.
6. Apply icon and behavior patterns consistently.
7. Review responsive and cross-platform behavior.
8. Verify the final layout in the running application.

## Layout Principles

- Prefer semantic containers over arbitrary nested panels.
- Centralize styles that are shared across multiple views.
- Keep components focused and reusable.
- Avoid duplicating visual properties in every control.
- Use behaviors for interaction logic where appropriate.
- Do not introduce converters when a simpler binding or behavior is available.
- Keep visual structure understandable to maintainers.

## Quality Checklist

- Layout hierarchy is easy to follow.
- Shared styles are reused.
- Containers match their semantic purpose.
- Icons use consistent sizing and alignment.
- Behaviors are separated from presentation.
- Component nesting is reasonable.
- Themes remain consistent.
- Views are tested at expected window sizes.

## Repository Contents

- `SKILL.md`: Main Avalonia layout instructions.
- `themes.md`, `containers.md`, `icons.md`, `behaviors.md`, `components.md`: Focused layout guides.
- `README.md`: Installation and design workflow.

## Practical Principle

Good XAML is not the XAML with the fewest lines. It is the XAML that communicates structure clearly and avoids duplicating decisions across the application.
