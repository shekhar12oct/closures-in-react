# 🔒 closures-in-react

A focused guide to understanding **JavaScript closures** in the context of **React** development. This repo breaks down common closure-related behaviors in functional components, hooks, and event handlers—so you can write cleaner, bug-free React code.

---

## 🧠 What Are Closures?

Closures are a foundational JavaScript concept where an inner function has access to variables defined in its outer scope—even after that outer function has finished executing.

In React, closures come into play often—sometimes in subtle ways—especially with:

- useEffect
- useCallback
- useRef
- Event handlers
- setState closures

---

## 📦 What's Inside

- 🔁 **Stale closures in useEffect**
- 🔄 **Closures with `setInterval` and `setTimeout`**
- 📥 **Event handlers holding onto old state**
- 🧵 **Using `useRef` to avoid stale closures**
- 💡 **Best practices to avoid common bugs**
