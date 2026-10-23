# Quantum Caesar Cipher & Reversible Logic Lab (QENC/LAB)

A sophisticated cyber-brutalist web application bridging classical cryptographic models (Caesar Cipher, ASCII mapping) with quantum information principles and information-lossless reversible gate logic (CNOT, Binary-to-Gray Code transformations).

---

## 🛠️ System Architecture & Core Modules

The application is structured into three dedicated modular views:

1. **01. Caesar Cipher & ASCII Mapping**
   - Translates raw plaintext strings into standard ASCII numerical index values.
   - Applies cryptographic shift vectors via modulus formulas: $x = \text{ASCII} - 64$, $Z = (x + k) \bmod 256$.
   - Converts shifted output into precise 8-bit binary registers ($a_7 \dots a_0$) for quantum compatibility.

2. **02. Reversible CNOT & Gray Code Conversion**
   - Simulates quantum Controlled-NOT (CNOT) gate architecture executing bitwise XOR ($\oplus$) operations across qubit registers without thermal dissipation or data loss.
   - Computes forward Gray code transformations ($g_7 = a_7$, $g_i = a_{i+1} \oplus a_i$).
   - Validates system reversibility through lossless backward decoding ($a_i = a_{i+1} \oplus g_i$).

3. **03. Live Trace & Report Export**
   - Renders comprehensive real-time step-by-step transformation tables.
   - Provides instant text-file export functionality (`.txt`) containing complete execution logs and trace metrics for academic documentation.

---

## 🎨 Design & Aesthetic

* **Aesthetic Style:** Cyber-Brutalism featuring high-contrast structural grids, coordinate markers, and raw technical layouts.
* **Dual Theme Engine:** Seamlessly toggle between Dark Mode and Light Mode via the header toggle button (`🌙 / ☀️`).
  * **Dark Theme:** Built on *Hēi Sè Black* (`#142030`) and *Blue Whale* (`#1E3442`) with *Stellar Strawberry* (`#FF5C8D`) highlights.
  * **Light Theme:** Built on *Siesta Tan* (`#E9D8C8`) and *Grauzone* (`#85A3B2`) with *Pico Eggplant* (`#732553`) accents.
* **Interactive Experience:** Custom cursor with an integrated JavaScript sparkle/particle trail effect.

---
