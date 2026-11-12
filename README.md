# Open World Game

**Full 3D open-world game** built with Godot 4.

Now with **automatic Android APK builds** via GitHub Actions.

---

## How to get the APK (No PC needed)

1. Go to the **Actions** tab of this repository:  
   https://github.com/afnan-ab/open-world-game/actions

2. Click on the latest **Build Android APK** workflow run (or trigger it manually with "Run workflow").

3. Wait until it finishes (green checkmark).

4. Scroll down to **Artifacts**.

5. Download **OpenWorldGame-APK**.

6. Unzip it and install the `.apk` on your Android phone.

> You may need to allow "Install from unknown sources" in your phone settings.

---

## Controls (on phone)

Currently keyboard/mouse oriented. For best mobile experience you can later add virtual joystick + look pad in Godot.

- Move: WASD (or connect a Bluetooth controller)
- Look: Mouse / touch drag (limited)
- Jump: Space
- Sprint: Shift

---

## Project Info

- Engine: Godot 4.3
- Type: Full native 3D game (not HTML)
- Features: First-person controller, large terrain, quality lighting, shadows, fog
- Package name: `com.afnan.openworldgame`

---

## Manual trigger

You can force a new APK build anytime:

1. Go to **Actions** tab
2. Select **Build Android APK**
3. Click **Run workflow** → **Run workflow**
