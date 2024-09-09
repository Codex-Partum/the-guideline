# the codex partum guideline

## Contents
- [Naming conventions](#naming-conventions)
- [Asset naming conventions](#asset-naming-conventions)
- [Syntax and formatting](#synax-and-formatting)

## Naming Conventions

We always want to ensure that all of our classes and settings are meaningfully named in a clean manner.

**Importanly, we use:**
- lowercase
- [BEM-like naming](#bem-like-naming)
- Only use `class` and never `id`
    - `id` is used for data purposes

### Asset naming conventions

PLS follow this template/format when naming ur assets

**[Project]-[Message role/alert type]-[Asset type]-[Name]-[Variant]-[Extra info]**

Possible asset types:
- Accent (general)
- Meta (pinned to username)

Possible message roles:
- Broadcaster
- Moderator
- Subscriber
- VIP (rarely used)
- Normal

Possible alert types:
- Subscribe
- Tip
- Cheer

For example:
```
Frog-Subscriber-Accent-Branch-InsideL-Overlay20.svg
Frog-Moderator-Accent-Star-OutsideMR-Overlay20.svg
```

## Syntax and formatting
*based off BEM syntax*

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

