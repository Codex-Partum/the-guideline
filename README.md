# the lumo lab guidebook

## Contents
- [Naming conventions](#naming-conventions)
- [Syntax and formatting](#synax-and-formatting)

## Naming Conventions

We always want to ensure that all of our classes and settings are meaningfully named in a clean manner.

**Importanly, we use:**
- lowercase
- [BEM-like naming](#bem-like-naming)
- Only use `class` and never `id`
    - `id` is used for data purposes

### BEM-like naming

We split class components into 3 groups:
- **Block** - The root of the component
- **Element** - A component of the block
- **Modifier** - A variant of the block

For example:
```css
.chat-accent {}
.chat-accent__line {}
.chat-accent--jellyfish {}
```

Here we can see that `.chat-accent {}` is the block/component.
`.chat-accent__line {}` is a part of the component
`.chat-accent--jellyfish {}` is a variant of the `chat-accent`.