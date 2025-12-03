# PT-BR Math Expert

**A standalone, high-performance keyboard layout designed for polymaths, scientists, engineers, and typographers.**

This layout extends the standard Brazilian Portuguese (ABNT2) keyboard with a comprehensive set of Unicode symbols for Calculus, Logic, Set Theory, Physics, Chemistry, and Typography, without breaking standard input.

⚠️ **Compatibility Note:** This is an **XKB** layout file designed specifically for **Linux distributions** (Arch, Ubuntu, Fedora, etc.) running X11 or Wayland (KDE/GNOME). It is **not directly compatible** with Windows or macOS without specific translation tools.

---

## 📸 Screenshots

![Keyboard Layout](images/keyboard_layout.png)
*View of levels 1 to 4, showing operators, letters and various characters.*

## ✨ Key Features

* **Hybrid Math Numpad:** Access navigation, numbers, superscripts (AltGr), and subscripts (AltGr+Shift) seamlessly.
* **Logic & Sets:** Symbols like `∀` `∃` `∈` `ℚ` `ℝ` grouped by semantic zones (QWE for Sets, ASD for Calculus).
* **Physics & Geometry:** `∇` `∂` `∆` `∠` `Ω` accessible on the main block.
* **Mnemonic Assimilation:** Keys are mapped by logic rather than random shapes, ensuring instant recall. Here are some examples:
    * **R** holds `ℝ` (Real) and `√` (Root).
    * **C** holds `ℂ` (Complex) and `ℵ` (Cardinality).
    * **Q** holds `ℚ` (Quotient/Rational) and `⇌` (Reaction Quotient).
    * **8** holds `∞` (Infinity) and `∝` (Proportionality).
* **Typographic Accents:** Includes Dead Macron ($ā$), Vector Arrow ($\vec{v}$), and Newton Dot ($\dot{x}$).

## 💡 Recommended Workflow (Greek Alphabet)

While this layout includes the most frequent Greek variables ($\pi, \sigma, \mu, \Omega, \phi$), it avoids cluttering the map with the entire Greek alphabet.

**Best Practice:**
For advanced mathematics involving extensive Greek notation, configure your Desktop Environment (KDE/GNOME) to have at least **two layouts**:
1.  **PT-BR Typographic** (Primary/Symbols)
2.  **Greek (Simple)** (Secondary)

Use a shortcut (e.g., `Super+Space` or `Alt+Shift`) to toggle instantly between Latin/Math and Greek input.

## 🚀 Installation

This is a **standalone** layout. You do not need to edit system XML rules.

1.  Download the `custom` file from the `symbols` folder in this repository.
2.  Copy it to the XKB symbols directory:
    ```bash
    sudo cp custom /usr/share/X11/xkb/symbols/
    ```
    *(Note: If you already have a 'custom' file, back it up first).*

3.  **Apply via KDE Plasma / GNOME:**
    * Go to **System Settings > Input Devices > Keyboard > Layouts**.
    * Click **Add Layout**.
    * Select **"Any Language"** (or clear filters).
    * Search for **"A user-defined custom Layout"**.
    * **Important:** Add it to the list, but **keep it below** your standard layout (e.g., standard Portuguese 'br') to prevent `AltGr` conflicts with Desktop Environment shortcuts. Use your system's shortcut (e.g., `Super+Space`) to switch to it when needed.

4.  **Log out and Log in** to ensure XKB caches are cleared.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Created by [Roger Júnio Gonçalves Gamito](https://github.com/rogerjgamito)*
