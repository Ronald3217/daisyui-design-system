# Page Templates

> Complete page templates ready to copy-paste.

---

## Login Page

```html
<div class="min-h-screen flex items-center justify-center bg-base-200">
  <div class="card w-full max-w-md bg-base-100 shadow-xl">
    <div class="card-body">
      <h2 class="card-title justify-center text-2xl mb-4">Welcome Back</h2>
      <div class="form-control">
        <label class="label"><span class="label-text">Email</span></label>
        <input type="email" placeholder="email@example.com" class="input input-bordered" />
      </div>
      <div class="form-control">
        <label class="label"><span class="label-text">Password</span></label>
        <input type="password" placeholder="••••••••" class="input input-bordered" />
      </div>
      <button class="btn btn-primary mt-4">Login</button>
    </div>
  </div>
</div>
```

---

## Dashboard

```html
<div class="navbar bg-base-200 rounded-box mb-4">
  <div class="flex-1"><a class="btn btn-ghost text-xl">Dashboard</a></div>
</div>

<div class="stats stats-vertical lg:stats-horizontal shadow mb-4">
  <div class="stat"><div class="stat-title">Users</div><div class="stat-value">1,234</div></div>
  <div class="stat"><div class="stat-title">Revenue</div><div class="stat-value">$8,900</div></div>
</div>

<div class="grid grid-cols-1 md:grid-cols-3 gap-4">
  <div class="card bg-base-200"><div class="card-body"><h2 class="card-title">Card</h2></div></div>
</div>
```