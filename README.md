<h1>
  <img src="https://github.com/user-attachments/assets/1eff2941-7889-4587-be6d-da86b6900069" width="95" align="left" style="margin-right:10px">
  earthPlace
</h1>

**World-locked Persistent AR Voxel Platform**

---

### Download & Test

- [iOS Closed Beta](https://testflight.apple.com/join/fPfRkrbH)
- [Android Closed Beta](https://appdistribution.firebase.dev/i/0f55bd682b2cd0d3)
- [Latest builds](../../releases)

[Project page](https://nourelfangary.com/projects/earthplace) · [Privacy policy](https://nourelfangary.com/projects/earthplace/privacy) · [Support](https://nourelfangary.com/projects/earthplace/support)

> This repository hosts public documentation and release builds for earthPlace. The source code is private. All rights reserved — no license is granted for the reproduction, modification, or distribution of the application or its assets.

earthPlace is a multiplayer augmented reality platform for collaborative voxel creation anchored to real-world locations. When players are in the same physical space, they automatically localize into a shared session where they can build and interact with persistent structures together in real-time, seamlessly blending digital creation with the physical world.

<div align="center">
  <table>
    <tr>
      <td rowspan="2">
        <img src="https://github.com/user-attachments/assets/b3f96473-52f6-4394-88ba-a932417f7979" height="420" alt="AR Voxel Animation">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/0abad5c4-40c0-4965-8b3f-8055ee8c1807" width="200" height="200" alt="bike">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/ae544fc9-70b1-48f4-8134-ebb373d35518" width="200" height="200" alt="spiral_thing">
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/f8b5a766-b91f-459a-a602-a21b970804b2" width="200" height="200" alt="heart">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/0cd45c5a-c2a6-4f08-a853-bc49de5a1751" width="200" height="200" alt="torch">
      </td>
    </tr>
  </table>
</div>

## Features

### World Localization

Upon launch, the application:

1. **Connects to the backend server** to retrieve available map bindings
2. **Identifies device world position** using device GNSS
3. **Localizes to existing maps** if available within the current area
4. **Prompts for area scanning** if no maps exist, allowing users to create new map bindings

### Multiplayer Sessions

- **Cross-platform compatibility** - Users on mobile and HMD devices can interact in the same session
- **Synchronized voxel placement** - All players see blocks in the exact same world-anchored locations
- **Real-time collaboration** - Multiple users can build together simultaneously
- **Persistent storage** - Voxel data and blocks persist across sessions

## Device Requirements

**iOS**
- iOS 15.0 or later
- ARKit-compatible device (Pro models with LiDAR recommended for best AR performance)

**Android**
- Android 7.0 (API 24) or later
- ARCore-compatible device

All platforms request location and camera permissions on first launch.

## Reporting Bugs & Requesting Features

Found a bug or have an idea? Open an issue:

- [Report a bug](../../issues/new?template=bug_report.yml)
- [Request a feature or share feedback](../../issues/new?template=feature_request.yml)
- [Browse existing reports](../../issues)

## Attributions

UI icons and assets used in this project:

- **Cube** (app icon) — by Royyan Wijaya, from [Flaticon](https://www.flaticon.com/)
- **Globe** (app icon background) — by sm wizard, from [Vecteezy](https://www.vecteezy.com/)
- **Interface icons** (refresh, back, settings, share, invite, undo, timeline and the rest) — [Lucide](https://lucide.dev/), copyright Lucide Contributors ([ISC License](https://github.com/lucide-icons/lucide/blob/main/LICENSE))
- **Line icons** (pencil, eye, trash) — [MynaUI Icons](https://mynaui.com/icons) by Praveen Juge ([MIT License](https://github.com/praveenjuge/mynaui-icons))
- **Eraser** — "Eraser Tool 3D Icon" by M Wildan Cahya Syarief, from [Iconscout](https://iconscout.com/)
- **Color dropper** — "Color Picker 3D Icon" by Soni Sokell, from [Iconscout](https://iconscout.com/)
- **Recenter** — "Target" icon by Anggara, from [Flaticon](https://www.flaticon.com/free-icon/target_5076994)
- **3D pencil** — "A Yellow Pencil with a Pink Eraser and Silver Band" by Nilufa Yeasmin, from [Vecteezy](https://www.vecteezy.com/png/70056639-a-yellow-pencil-with-a-pink-eraser-and-silver-band-isolated-on-transparent-background)
- **Select cursor** — "Hand Cursor Icon 3D Render for UI UX Design" by Forida Akther Rimu, from [Vecteezy](https://www.vecteezy.com/png/69258298-hand-cursor-icon-3d-render-for-ui-ux-design)
- **Fonts** — Roboto Slab by Christian Robertson, and Google Sans Code by the Google Sans Code Project Authors, both under the [SIL Open Font License 1.1](https://openfontlicense.org/)

## Legal

© 2026 Nour Elfangary. All Rights Reserved.  
earthPlace™ is a trademark of Nour Elfangary.
