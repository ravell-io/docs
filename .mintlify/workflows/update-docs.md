---
name: "Update docs"
on:
  push:
    - repo: "ravell-io/ravell-rails"
    - repo: "ravell-io/Ravell"
context:
  - repo: "ravell-io/website"
---

Automatically detect when the documentation isn't up to date based on new added feature and improve it.
