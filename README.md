# LegacyXOS
Linux distro im working on it by VibeCoding pls no hate still Unstable not Utilizable because im still creating it the status is 0%
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🚀 LegacyXOS v1.0

> **The World's First Monolithic Desktop Operating System Written Entirely in a Single `Main.java` File.**  
> *Zero Assembly. Zero C Kernel. Zero Sanity. 100% Pure Java SDK 27.*  (As still predicting bro not secure🥀🥀)

---

## 💻 Architecture Overview

LegacyXOS redefines Operating System architecture by throwing away 40 years of computer science best practices:

* **Custom Java Kernel:** Forget Linux, C, and Assembly. We wrote our own x86_64 Kernel directly inside `Main.java` using Java 27 and sheer willpower. Kernel Panics are now handled via `try-catch` blocks!
* **Single File Monolith:** The entire Kernel, UI engine, Vulkan/OpenGL graphics stack, and Package Manager live inside **ONE SINGLE SOURCE FILE**: `Main.java`.
* **Graphics Engine:** Integrated Vulkan / OpenGL / WebGL direct abstraction matrix.
* **Windows Compatibility:** Built-in Proton-CachyOS translation layer running pure Java bytecodes for x86_64 binaries.
* **Package Manager (`xnf`):** Built-in "X-No-File" manager that downloads pre-compiled binaries from cloud storage.
* **Claring:** May this will not be possible or it will be possible. We just predicted like this. I'm not responsible for all...

---

## 📦 Package Management (`xnf`)

LegacyXOS does NOT pay for expensive VPS or CDN servers. Instead, we use GitHub as an unauthorized, totally free cloud storage engine to host 150GB+ of raw pre-compiled packages!

```bash
# How to install Steam on LegacyXOS
sudo xnf install steam
