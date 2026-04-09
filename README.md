# ⚡ About Me — PowerApps Developer

I don’t just build apps—I design them to work **properly at scale**.

Most applications fail not because they don’t work, but because they ignore platform limits. My approach is simple: **plan the flow, respect constraints, and engineer around them**.

---

## 🧠 How I Think

I always start with **flow before anything else**.

No UI. No coding.
Just a clear, structured path of how the app should behave.

Because building without a defined flow leads to:

* messy logic
* broken navigation
* hard-to-maintain apps

Development should be **planned and systematic**, not guesswork.

---

## ⚙️ My Approach to Building

### 1. Flow First

I define:

* user journey
* data movement

If the flow is wrong, everything else will break later.

---

### 2. Choose the Right Data Strategy

I don’t treat data sources equally:

* **SharePoint** → fast to build, good for small to medium scale
* **Dataverse** → used when scale and performance demand it
* **Collections** → temporary session storage, not a database

Choosing the wrong one early leads to limitations later.

---

### 3. Multi-Screen Over Single-Screen

Single screen looks clean—but becomes hard to manage.

I prefer **multi-screen apps** because:

* easier to debug
* easier to maintain
* less mental overhead

Some UI reload is acceptable if it improves structure.

---

### 4. Clean and Readable Logic

I avoid overly nested formulas whenever possible.

Instead:

* `_var` → local context
* `_global` → global variables
* `_col` → collections

Readable logic is easier to maintain than “smart but messy” formulas.

---

### 5. Performance Matters

I actively avoid patterns that cause lag:

* minimize container nesting
* use positioning (X, Y, Width) when possible
* use scrollable canvas instead of heavy containers

Small decisions here make a big difference in real apps.

---

## 🚫 My Non-Negotiable: No Delegation

I don’t ignore delegation warnings—I design around them.

### My process:

1. Identify delegation issue (usually data fetching)
2. Move logic to Power Automate
3. Use **Get Items + Select** (remove unnecessary columns, keep ID)
4. Return clean data to PowerApps

---

### ⚡ Scaling Strategy

To handle large data (up to 100,000+ rows):

* Use **Power Automate** to bypass delegation limits
* Implement **pagination** to avoid the 120-second timeout
* Accept the trade-off: more resources, but scalable solution

Optional:

* Apply **auto-archiving** for long-term data control

---

## 🧩 UI Philosophy

I don’t believe in pure “free flow” design.

Best approach:

> **Controlled flexibility (free flow) + fixed layout**

Why:

* prevents UI breaking
* keeps consistency
* avoids elements “flying everywhere”

---

## 🧼 Development Discipline

* No symbols in SharePoint column names
* Follow relational naming conventions
* Group lists logically
* Clear naming for flows:
  `App Name | Function (e.g. Fetch Patients Data)`

Everything is designed for **clarity and maintainability**.

---

## 💬 My Take on “Basta Gumana” or in english "As long as it works"

We all say it—but it’s not the goal.

It means:

> “This works for now. We’ll fix it later.”

If that mindset stays permanent, growth stops.

---

## 🎯 Final Thought

Anyone can build a working app.

What matters is:

* how you design it
* how it handles scale
* how maintainable it is over time

I focus on building apps that don’t just work—
but **continue to work when it actually matters**.

---
