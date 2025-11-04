# 💿 The BrokenRecord

A demonstration of how **JNI** (Java Native Interface) can bypass the **`final`** keyword to mutate Java `record`s, succeeding where Reflection and `Unsafe` fail.

Ever wondered if records could be mutated at runtime?

---

## ⚠️ Disclaimer: Do Not Use This in Production

This is a **technical demostration**, not a tool.

Modifying `final` fields, especially on immutable objects like `record`s, is a **direct violation of the Java Language Specification** and the Java Memory Model. Doing this in a real application will lead to undefined behavior, silent data corruption, and catastrophic crashes.

**This is for learning, not for hacking.**

---
