# Tokyo Drift Save Editor (PSP / ULUS10198)

A browser-based save editor for **The Fast and the Furious (2006)** on PSP (`ULUS10198`). Runs on a low effort html.

Built with Claude Because I Suck, And since realizing nobody had made a proper save editor for this game.

> **⚠️ ALWAYS BACK UP YOUR SAVE FIRST.** I tested this against my own legit progression saves and i haven't had any problem but just incase keep one, experimental stuff is marked for a reason.

---

## What It Can Do (v0.4.1)

* **Performance Parts:** Set any upgrade slot from Level 1 to 5 (or max everything out at once).
* **Cross-Car Body Parts:** Swap **2,339 body parts** across 14 slots (body kits, bonnets, bumpers, skirts, spoilers, lights, exhausts, neon, charms, etc.) from Veilside, C-West, Spoon, and more, including putting parts from one car onto another.
* **Engine Swaps:** Install any of the **14 aftermarket swaps** or stock engines, with built-in warnings for cars that restrict swaps.
* **Wheels & Fitment:** Pick from **203 wheel models** (102 stock, 98 aftermarket, and 3 unused hidden wheels) and set custom front/rear rim sizes (inches) and tyre widths (mm).
* **Garage Management:** Clone cars, add any factory-stock car from the game's internal list, import cars from another `SECURE.BIN` save, or delete cars.
* **Tune Shop Bypass (Experimental):** This shit barely works bruh ain't gon lie. ✌️😭💔
* **Unlocks & Cash:** Unlock cars (Dealership ones.) upgrades, stickers, shop discounts, cash.

### Still Not Decoded Yet
* Paint colours
* Driver wins / Losses stats
* Whatever Y'all Suggest

---

## How to Use It (PPSSPP)

The PSP normally encrypts `SECURE.BIN`. You need a **decrypted** save (`524,288 bytes`) for the editor to read it:

1. **Turn off save encryption in PPSSPP:**
   * Open `PSP/SYSTEM/ppsspp.ini` and set `EncryptSave = False`
2. **Make a decrypted save:**
   * Launch *The Fast and the Furious* (`ULUS10198`), load your profile, and save your game once in-game.
3. **Edit your save:**
   * Open the **Tokyo Drift Save Editor** in your browser.
   * Load `SECURE.BIN` from `PSP/SAVEDATA/ULUS10198.../` (Keep a backup copy first.)
   * Tweak your cars, parts, cash, or unlocks, then tap **Download patched save (zip)**.
4. **Replace the file:**
   * Extract `SECURE.BIN` from the downloaded zip and overwrite the one inside your `PSP/SAVEDATA` folder.
   * Load your save in PPSSPP and yeah that's it bro.

---

## Credits & Notes

* **Created by:** GFreddy (This guy is a fraud bruh, It was made by **Claude**, but if you wanna talk to this bum, dm .benxt on disocrd.)
* **Compatibility:** Built and tested on the North American PSP release (`ULUS10198`).


### **[Launch the Tokyo Drift Save Editor in Your Browser](https://gfreddyworkz.github.io/The-Fast-and-The-Furious-Tokyo-Drift-Editor/)**
