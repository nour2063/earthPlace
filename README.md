<h1>
  <img src="https://github.com/user-attachments/assets/1eff2941-7889-4587-be6d-da86b6900069" width="95" align="left" style="margin-right:10px">
  earthPlace
</h1>

**World-locked Persistent AR Voxel Platform**

---

### Download & Test

- [iOS Beta (TestFlight)](https://testflight.apple.com/join/fPfRkrbH)
- [Android Beta (Firebase)](https://appdistribution.firebase.dev/i/7df9c87a09c55992)
- [Latest builds](../../releases) — direct APK and IPA downloads

> This repository hosts public documentation and release builds for earthPlace. The source code is private. All rights reserved — no license is granted for the reproduction, modification, or distribution of the application or its assets.

earthPlace is a multiplayer augmented reality platform for collaborative voxel creation anchored to real-world locations. When players are in the same physical space, they automatically localize into a shared session where they can build and interact with persistent structures together in real-time, seamlessly blending digital creation with the physical world.

<div align="center">
  <table>
    <tr>
      <td rowspan="2">
        <img src="https://github.com/user-attachments/assets/fbafba71-d43a-4e45-b346-c69383236f01" height="420" alt="AR Voxel Animation">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/558c0a06-8b2c-4217-886f-0c1ec9b7ff82" width="200" height="200" alt="bike">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/8a2935d0-213f-4685-af9e-ee4ef31f8163" width="200" height="200" alt="spiral_thing">
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/029fcfba-35ee-4880-b74b-0b5a8f0b6387" width="200" height="200" alt="heart">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/b0673869-98e8-46f1-8ff1-fffa7aa55184" width="200" height="200" alt="torch">
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

## Attributions

UI icons and assets used in this project:

- **Cube** (app icon) — by Royyan Wijaya, from [Flaticon](https://www.flaticon.com/)
- **Globe** (app icon background) — by sm wizard, from [Vecteezy](https://www.vecteezy.com/)
- **Interface icons** (gray line icons, navigation arrow, plus, pencil) — [MynaUI Icons](https://mynaui.com/icons) by Praveen Juge ([MIT License](https://github.com/praveenjuge/mynaui-icons))
- **Invite** — "User Avatar" icon by SeyfDesigner, from [Flaticon](https://www.flaticon.com/free-icon/user-avatar_8188374)
- **Eraser** — "Eraser Tool 3D Icon" by M Wildan Cahya Syarief, from [Iconscout](https://iconscout.com/)
- **Color dropper** — "Color Picker 3D Icon" by Soni Sokell, from [Iconscout](https://iconscout.com/)
- **Quadrilateral icon** (and its grayscale variant) — from [Iconscout](https://iconscout.com/)
- **Gallery icon** (placeholder thumbnail) — "3D Gallery Icon with Mountains and Sun" by Arman Hasan, from [Vecteezy](https://www.vecteezy.com/png/69002876-3d-illustration-of-3d-gallery-icon-with-mountains-and-sun-isolated-on-transparent-background)
- **Map illustration** — "Cute Map 3D Rendered Style" (#21443558) by Grapict Studio, from [Pngtree](https://pngtree.com/)
- **Share** — "Share" icon by Bankume, from [Flaticon](https://www.flaticon.com/free-icon/share_4855052)

## Legal

© 2026 Nour Elfangary. All Rights Reserved.  
earthPlace™ is a trademark of Nour Elfangary.
