# Coding Standards - daisyUI Design System Skill

This document defines the coding standards and conventions for the daisyUI Design System Skill project.

## Project Overview

This is a **reference knowledge base** for daisyUI (a Tailwind CSS component library). It provides:
- 66 component references
- 34+ framework installation guides
- Theme system documentation
- Cross-patterns and templates

---

## Code Standards

### 1. Class Pattern Convention

**Always replace placeholder patterns with actual daisyUI classes:**

```
$$componente $$componente-$$variant  →  componente variant
```

| Placeholder | Example Output |
|-------------|-----------------|
| `$$button $$button-$$variant` | `btn btn-primary` |
| `$$input $$input-$$variant` | `input input-bordered` |
| `$$badge $$badge-$$variant` | `badge badge-secondary` |
| `$$alert $$alert-$$variant` | `alert alert-warning` |

### 2. Color Variants

Use consistent color variants across all components:

| Variant | Use Case |
|---------|----------|
| `primary` | Main brand actions, primary CTAs |
| `secondary` | Secondary actions, complementary elements |
| `accent` | Highlights, decorative accents |
| `neutral` | Text, backgrounds, neutral states |
| `info` | Informational messages |
| `success` | Positive feedback, success states |
| `warning` | Caution messages, warnings |
| `error` | Error states, destructive actions |

### 3. Style Modifiers

Apply consistent style modifiers:

| Modifier | Description |
|----------|-------------|
| `outline` | Bordered, transparent background |
| `soft` | Filled background with lighter shade |
| `ghost` | Transparent background, hover reveals fill |
| `dash` | Dashed border style |
| `link` | Text styled as link |

### 4. Responsive Classes

Follow standard Tailwind breakpoints:

```
sm  - 640px
md  - 768px
lg  - 1024px
xl  - 1280px
2xl - 1536px
```

### 5. Size Classes

Use consistent sizing scale:

```
xs, sm, md, lg, xl, 2xl
```

---

## File Naming Conventions

- Reference files: `NN. description-category.md` (e.g., `59. components-button.md`)
- Use lowercase with hyphens for all file names
- Group related files in appropriate directories

---

## Documentation Standards

### Component References

Each component reference should include:
1. Description and purpose
2. Class syntax/structure
3. Size and color variants
4. Common examples
5. Accessibility notes where applicable

### Installation Guides

Each framework guide should include:
1. Prerequisites
2. Installation steps
3. Configuration (if needed)
4. Verification/quick start example

### Quick Reference Files

Maintain organized tables with:
- Clear headers
- Consistent formatting
- Practical examples
- Cross-references to full docs

---

## Quality Guidelines

### 1. Accuracy
- Verify all daisyUI classes against official documentation
- Test component combinations in real scenarios
- Cross-check theme/color references

### 2. Completeness
- Include all available variants for each component
- Document both common and edge case usages
- Provide practical, copy-paste examples

### 3. Consistency
- Use consistent terminology throughout
- Follow the same structure for similar components
- Match the formatting of official daisyUI docs

### 4. Clarity
- Keep examples simple and focused
- Use comments to explain complex combinations
- Include responsive considerations in examples

---

## Version Compatibility

- Target: **daisyUI v5.5.19**
- Tailwind CSS: **v3.x**
- Update version references when upgrading

---

## Theme System Standards

### Available Themes

```
light, dark, cupcake, bumblebee, emerald, corporate, synthwave,
retro, cyberpunk, valentine, halloween, garden, forest, aqua,
lofi, pastel, fantasy, wireframe, black, luxury, dracula, cmyk,
autumn, business, acid, lemonade, night, coffee, winter
```

### CSS Variables
- Use standard theme CSS variables
- Reference `THEME_COLORS.md` for variable patterns

---

## Maintenance

### Regular Updates
- Review daisyUI releases for new/changed components
- Update installation guides for framework updates
- Sync with official documentation changes

### Validation Checklist
- [ ] All component classes verified
- [ ] Installation steps tested (or marked as untested)
- [ ] Links to official docs valid
- [ ] Consistent formatting across files
- [ ] Version information current

---

## Related Documentation

| File | Purpose |
|------|---------|
| `QUICK_REFERENCE.md` | Sizes, colors, breakpoints |
| `THEME_COLORS.md` | Theme system details |
| `CROSS_PATTERNS.md` | Component combinations |
| `TEMPLATES.md` | Complete page templates |
| `TROUBLESHOOTING.md` | Common issues |

---

*Version: 5.5.19*
*Last Updated: 2026*