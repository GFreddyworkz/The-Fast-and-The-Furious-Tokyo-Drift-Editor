# Tokyo Drift Save Editor (PSP / ULUS10198)

A browser-based save editor for **The Fast and the Furious (2006)** on PSP (`ULUS10198`). Runs on a low effort html, on phones, PCs and any browser.

Built with Claude Because I Suck, And since realizing nobody had made a proper save editor for this game.

> **⚠️ ALWAYS BACK UP YOUR SAVE FIRST.** I tested this against my own legit progression saves and i haven't had any problem but just incase keep one, experimental stuff is marked for a reason.

---

## What It Can Do (v0.4.3)

- **Performance Parts:** Set any upgrade slot from Level 1 to 5 (or max everything out at once).
- **Tyres:** Stock, **Grip 1-5** and **Drift 1-5**, with the game's own values.
- **Advanced Values (Experimental):** Type exact numbers into a part to go **past level 5**: power and torque, suspension, gear ratios, NOS, tyre grip, brake strength and more. The game uses the numbers you type. ⚠️ Going crazy (around a million and up) can black out the screen while the game keeps running, so build up slowly.
- **Engine Curve (Experimental):** Scale the torque and rpm of a swapped-in engine, or set its max clutch torque.
- **Cross-Car Body Parts:** Swap **2,339 body parts** across 14 slots (body kits, bonnets, bumpers, skirts, spoilers, lights, exhausts, neon, charms, etc.) from Veilside, C-West, Spoon, and more, including putting parts from one car onto another.
- **Body Paint:** The game's **30 paint-shop colours** or any **custom RGB colour**, with Metallic, Matt or Gloss (Pearlescent too, even though the game's own shop doesn't have it).
- **Rim Colour:** Same colours and effects, for your wheels.
- **Engine Swaps:** Install any of the **14 aftermarket swaps** or stock engines, with built-in warnings for cars that restrict swaps.
- **Wheels & Fitment:** Pick from **203 wheel models** (102 stock, 98 aftermarket, and 3 unused hidden wheels) and set custom front/rear rim sizes (inches) and tyre widths (mm).
- **Garage Management:** Clone cars, add any factory-stock car from the game's internal list, add rival cars, import cars from another `SECURE.BIN` save, or delete cars.
- **Share a Car:** Turn any car into a **car code or file** (parts, tunes, paint, rims, vinyls and all) and send it to a friend. They paste it in and the car lands in their garage.
- **Health Check:** Every download is checked first. If the save looks broken, the editor blocks the download and tells you why.
- **Unlocks & Cash:** Unlock cars (Dealership ones.) upgrades, stickers, shop discounts, cash.

### What's New

- **v0.4.3:** Tyres (grip and drift), Advanced Values, Engine Curve, Rim Colour, Share a Car, Health Check, and a proper Info tab and Body Paint (30 colours or custom RGB).

### Still Not Decoded Yet

- Driver wins / Losses stats (not found as a plain number in the save, might be calculated by the game)
- Vinyl editing (the game's own vinyl editor does that fine)
- Whatever Y'all Suggest

---

## How to Use It (PPSSPP)

The PSP normally encrypts `SECURE.BIN`. You need a **decrypted** save (`524,288 bytes`) for the editor to read it:

1. **Turn off save encryption in PPSSPP:**
   - Open `PSP/SYSTEM/ppsspp.ini` and set `EncryptSave = False`
2. **Make a decrypted save:**
   - Launch *The Fast and the Furious* (`ULUS10198`), load your profile, and save your game once in-game.
3. **Edit your save:**
   - Open the **Tokyo Drift Save Editor** in your browser.
   - Load `SECURE.BIN` from `PSP/SAVEDATA/ULUS10198.../` (Keep a backup copy first.)
   - Tweak your cars, parts, paint, cash, or unlocks, then tap **Download patched save (zip)**.
4. **Replace the file:**
   - Extract `SECURE.BIN` from the downloaded zip and overwrite the one inside your `PSP/SAVEDATA` folder.
   - Load your save in PPSSPP and yeah that's it bro.

### Sharing a car

1. Pick the car at the top, go to the **Garage** tab and tap **Make a car code**.
2. Copy the code (or save it as a `.tdcar` file) and send it to a friend.
3. They open the editor, go to **Garage**, paste the code (or pick the file) and tap **Add this car to my garage**.

---

## Credits & Notes

- **Created by:** GFreddy (This guy is a fraud bruh, It was made by **Claude**.)
- **Compatibility:** Built and tested on the North American PSP release (`ULUS10198`).
- **Tested in the game:** performance parts, engine swaps, wheels, rim sizes, money, garage changes, tyres (grip and drift) and the Advanced Values panel. Part swaps, body paint, rim colour and car sharing are newer and have had less testing, so check them before relying on them.

### **[Launch the Tokyo Drift Save Editor in Your Browser](https://gfreddyworkz.github.io/The-Fast-and-The-Furious-Tokyo-Drift-Editor/)**
