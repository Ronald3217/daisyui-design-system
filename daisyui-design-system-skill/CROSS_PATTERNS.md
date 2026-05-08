# Cross-Component Patterns

> Common patterns for combining daisyUI components.

---

## Form: Input + Select + Checkbox + Button

```html
<div class="form-control">
  <label class="label"><span class="label-text">Email</span></label>
  <input type="email" placeholder="email@example.com" class="input input-bordered input-primary" />
</div>

<div class="form-control">
  <label class="label"><span class="label-text">Country</span></label>
  <select class="select select-bordered">
    <option>United States</option>
    <option>Canada</option>
  </select>
</div>

<button class="btn btn-primary">Submit</button>
```

---

## Modal with Form

```html
<label for="my-modal" class="btn">Open Modal</label>

<input type="checkbox" id="my-modal" class="modal-toggle" />
<label for="my-modal" class="modal cursor-pointer">
  <label class="modal-box relative">
    <h3 class="font-bold">Edit Profile</h3>
    <div class="form-control mt-4">
      <input type="text" class="input input-bordered" />
    </div>
    <div class="modal-action">
      <label for="my-modal" class="btn">Cancel</label>
      <button class="btn btn-primary">Save</button>
    </div>
  </label>
</label>
```

---

## Navbar + Drawer

```html
<div class="navbar bg-base-200 rounded-box">
  <div class="flex-none lg:hidden">
    <label for="my-drawer" class="btn btn-square btn-ghost">☰</label>
  </div>
  <div class="flex-1"><a class="btn btn-ghost text-xl">daisyUI</a></div>
</div>

<div class="drawer lg:drawer-open">
  <input id="my-drawer" type="checkbox" class="drawer-toggle" />
  <div class="drawer-side">
    <label for="my-drawer" class="drawer-overlay"></label>
    <ul class="menu w-80 min-h-full bg-base-200">
      <li><a>Item 1</a></li>
      <li><a>Item 2</a></li>
    </ul>
  </div>
</div>
```