# Contributing to Awesome Wear OS

Thanks for your interest in contributing! This guide explains how to add your project and what's accepted.

## Inclusion Policy

We accept:

- Apps available on Google Play Store or Github (or similar) releases
- Development tools and libraries
- Educational resources and guides
- Both free and paid content
- Open and closed source projects

> [!WARNING]
> At this time, we currently do not accept paid watch faces, except ones that are open-source.

Projects should be:

- Related to Wear OS
- Active and maintained
- Not violating any laws or Google Play policies
- Ready for production (not test only or demo)

## How to Submit

1. Fork this repository
2. Add your project following the format below
3. Submit a pull request
4. Ensure your PR description includes:
   - Brief description of your project
   - Why it belongs in the list
   - Confirmation that it's actively maintained

## Format Guidelines

### Source Code Indicators

Use these emojis to indicate the source code availability:

- `🔓` = Open-source project (code is publicly available)
- `🔒` = Closed-source project (code is private)

> [!IMPORTANT]
> Always include the appropriate emoji at the end of your entry to help users quickly identify project types.

### Basic Entry Format

```markdown
- [App Name](link) `emoji`
- [App Name](link) - Brief description `emoji`
```

For open source projects:

```markdown
- [App Name](store-link) ([source code](repo-link)) `🔓`
- [App Name](store-link) ([source code](repo-link)) - Brief description `🔓`
```

> [!TIP]
> Add a brief description after the link(s) if the app name isn't self-explanatory. Keep descriptions concise and focused on the main feature.

### Examples

> [!TIP]
> For open source projects, always link both the store listing and source code repository.

Closed source paid app:

```markdown
- [Amazing Watch Face](https://play.google.com/...) `🔒`
- [Sleep Monitor Pro](https://play.google.com/...) - Advanced sleep tracking with heart rate monitoring `🔒`
```

Open source free app:

```markdown
- [Cool Timer](https://play.google.com/...) ([source code](https://github.com/...)) `🔓`
- [Battery Widget](https://play.google.com/...) ([source code](https://github.com/...)) - Simple tile showing battery levels of watch and phone `🔓`
```

> [!WARNING]
> Ensure all links are permanent and point to Google Play or a GitHub release (or similar), not to specific versions or temporary locations.

> [!NOTE]
> Descriptions are optional but recommended for apps with non-obvious functionality.

### Category Structure

Apps should be placed in appropriate categories and subcategories:

```markdown
### Category Name

- [Free App 1](link) - short description of app `emoji`
- [Free App 2](link) - short description of app `emoji`

<details open>
<summary>🪙 Apps with in app purchases</summary>

<!-- Add your app here if it has IAPs -->
</details>

<details>
<summary>💰 Paid apps</summary>

<!-- Add your app here if it's paid -->
</details>
```

> [!NOTE]
> The free apps will come first. App's with in app purchases and that are paid will come after and will be collapsible so that users can see app's that align with their pricing preference.

> [!TIP]
> If your app fits multiple categories, choose the most relevant one or discuss in your PR which category makes the most sense.

### Need Help?

- Open an issue if you're unsure where to place your project
- Ask for clarification on any guidelines
- Suggest improvements to these contribution guidelines
