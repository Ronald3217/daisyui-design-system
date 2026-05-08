# Troubleshooting & Tips

> Common problems and solutions.

---

## Common Issues

| Problem | Solution |
|---------|-----------|
| Modal not centering | Add `modal-middle` |
| Drawer overlapping | Use `drawer-overlay` |
| Dropdown not opening | Add `tabindex="0"` |
| Input border ignored | Use `input-bordered` first |

---

## Tips

- Always use `form-control` for form elements
- Use semantic colors (`bg-primary`)
- Mobile-first approach
- Use `<dialog>` for accessible modals

---

## Debugging Checklist

- [ ] daisyUI plugin in tailwind.config.js?
- [ ] Config themes enabled?
- [ ] Base classes present?