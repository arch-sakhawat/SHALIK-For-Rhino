# Shalik for Rhino 8
### Parametric Architectural Modeling Suite (Commercial Software)

<div align="center">

<img src="assets/icon.png" width="128" height="128" alt="Shalik Logo" />
<br />
<img src="assets/author.png" width="140" height="140" style="border-radius: 50%; margin-top: 10px;" alt="Sakhawat Hosen Sumon" />

### **Created & Developed by Sakhawat Hosen Sumon**
Architect & Computational Software Developer  
Dhaka, Bangladesh

[🌐 Facebook Profile](https://www.facebook.com/sakhawat.sumon2) • [📺 YouTube Channel](https://www.youtube.com/@archsakhawat) • [📧 Email: arch.sakhawat@gmail.com](mailto:arch.sakhawat@gmail.com)

**All licenses, copyrights, and intellectual property held exclusively by Sakhawat Hosen Sumon.**

---

### 📥 [Download Official Installer: Shalik-1.0.4-Setup.exe](Shalik-1.0.4-Setup.exe?raw=true)
*(Compatible with Rhino 8.0+ on Windows 10 / 11 64-bit)*

</div>

---

> [!IMPORTANT]
> ### 💼 COMMERCIAL PAID SOFTWARE — NOT FREEWARE
> - **Commercial License Required**: Shalik is a proprietary, professional commercial software product developed for architectural practitioners, BIM modelers, and 3D visualization studios. It is **NOT** open source and **NOT** free of charge. A valid commercial activation key is required to use the software.
> - **Full Ownership of 3D Output**: All 3D models, geometry, BIM assemblies, and renderings created with Shalik belong **100% to you**. You can freely use them in commercial architectural projects, client deliverables, and construction documents with zero royalty fees.
> - **Redistribution Prohibited**: Sharing, re-hosting, or modifying the software binaries, packages, or licenses without express written permission is strictly prohibited by law.

---

## 🏛️ Suite Overview

**Shalik** is an advanced, high-performance parametric architectural suite built natively for **McNeel Rhinoceros 8** (Windows x64). It equips architects and designers with interactive generators capable of generating complex architectural building elements in seconds with live viewport preview, IBC/EN code compliance, automatic wall openings, and unit intelligence (Inches & Millimeters).

### ✨ Core Capabilities:
- **Interactive Viewport Display**: Real-time 3D wireframe and shaded preview in Rhino viewports while adjusting parameters before baking geometry.
- **Double-Click to Edit**: Double-click any previously generated door, window, stair, or railing in your Rhino viewport to reopen its parameter dialog and modify it in place.
- **Automatic Wall Openings**: `ArchDoorInWall` and `ArchWindowInWall` automatically cut precise openings through Rhino polysurface walls and insert parametric assemblies.
- **Parametric Presets**: Save and load custom architectural styles as JSON presets.
- **Organized Layering**: Automatically bakes elements onto standardized, color-coded sub-layers (`FRAME`, `PANEL`, `GLASS`, `HARDWARE`, `WALL_CORE`).
- **Dynamic Unit Scaling**: Built-in awareness for Imperial (Inches, Feet) and Metric (Millimeters, Centimeters, Meters) document settings.

---

## 🛠️ Included Architectural Tools

| Tool | Rhino Command | Description |
| :--- | :--- | :--- |
| **Door Generator** | `ArchDoor` / `ShalikDoor` | Modern single, double, unequal leaves, pivot, sliding, frame profiles, hardware, and glass inserts. |
| **Window Generator** | `ArchWindow` / `ShalikWindow` | Fixed, casement, sliding, awning, bifold, multi-pane grids, sills, and transom configurations. |
| **Staircase Generator** | `ArchStair` / `ShalikStair` | 10 stair systems: Sawtooth, Closed Housed, Central Mono-Stringer, Cantilevered Floating, Spiral, and Dogleg. |
| **Railing Generator** | `ArchRailing` / `ShalikRailing` | 10 railing types: Frameless glass shoe, glass standoff pins, post & clamp, cable rail, and balusters. |
| **Wall Generator** | `ArchWall` / `ShalikWall` | Parametric multi-layer walls with interactive polyline layout, mitered corners, and layer detailing. |
| **Escalator Generator** | `ArchEscalator` / `ShalikEscalator` | Commercial escalators and moving walkways with live 3D truss, step treads, and balustrades. |
| **Curtain Wall Facade** | `ArchCurtainWall` / `ShalikCurtainWall` | Modern facade grid generator with mullions, transoms, spandrels, and baseline alignment. |
| **Truss Generator** | `ArchTruss` / `ArchTruss2D` | Structural Pratt, Warren, Howe, and X-braced trusses in solid 3D or 2D planar centerline drafting. |
| **Space Truss Generator** | `ArchSpaceTruss` / `ShalikSpaceTruss` | Surface-driven 3D structural space frames with pyramid grids and MERO spherical nodes. |
| **Tree & Forest Array** | `ArchTree` / `ArrayTree` | Parametric 3D architectural vegetation (Softwood, Hardwood) and linear/radial forest scattering. |
| **Louver & Sunshade** | `ArchLouver` / `ShalikLouver` | Architectural brise-soleil, aerodynamic fins, vertical and horizontal sunshades. |
| **Pitch Roof Generator** | `ArchPitchRoof` / `PitchRoof` | Hip, gable, shed, and gambrel roofs with 6 tile/cladding types and timber/steel framing systems. |
| **Security & Privacy Grill** | `ArchGrill` / `ShalikGrill` | Architectural window grills and geometric screens with 12 distinct patterns and bar profiles. |
| **Window Blinds & Shades** | `ArchBlind` / `ShalikBlind` | Venetian, Vertical, Roller, and Matchstick window shades with customizable slat rotation angles. |
| **Road & Utility Pole** | `ArchRoad` / `ArchElectricPole` | Urban road corridors, asphalt curbs, sidewalks, crosswalks, street lights, and power poles. |
| **License & Suite Info** | `ArchAbout` / `ArchActivate` | Credits dialog, suite version diagnostics, and license activation management. |

---

## 💻 System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit).
- **Host Application**: **McNeel Rhinoceros 8** (version 8.0 or newer).
- **Hardware**: Standard 64-bit Intel/AMD CPU, 8 GB+ RAM, OpenGL 4.1-capable GPU.

---

## 🚀 Installation Guide

### Step 1: Download
Download the latest installer directly from this repository:
👉 [**Shalik-1.0.4-Setup.exe**](Shalik-1.0.4-Setup.exe?raw=true)

### Step 2: Install
1. Make sure **Rhino 8 is closed**.
2. Double-click `Shalik-1.0.4-Setup.exe`.
3. Follow the installation wizard. The installer automatically:
   - Deploys the plug-in (`Shalik.rhp`) to Rhino's official packages directory.
   - Registers the ribbon toolbar (`Shalik.rui`).
   - Configures command aliases in Rhino 8.
4. Click **Finish**.

### Step 3: Launch Rhino 8
1. Open Rhino 8.
2. The **Shalik** ribbon tab and toolbar will load automatically at the top of your workspace.

---

## 🔑 Activation & How to Purchase a License

When you first click any Shalik tool or run `ArchActivate`:

```
+--------------------------------------------------------------+
|             SHALIK ARCHITECTURE SUITE - ACTIVATION           |
+--------------------------------------------------------------+
| Status: NOT ACTIVATED                                        |
|                                                              |
| Machine ID:  [ SHLK-8A3F-4B1C-9D0E-7F2A ]  [ Copy ID ]       |
|                                                              |
| Instructions:                                                |
| Send this Machine ID to arch.sakhawat@gmail.com to obtain    |
| your commercial license key.                                 |
|                                                              |
| Activation Key:                                              |
| [ Paste your key here...                                   ] |
|                                                              |
|                    [ Activate License ]                      |
+--------------------------------------------------------------+
```

### Steps to Activate:
1. Click **Copy ID** to copy your unique Machine ID.
2. Send your Machine ID to **Sakhawat Hosen Sumon** via:
   - 📧 Email: **[arch.sakhawat@gmail.com](mailto:arch.sakhawat@gmail.com)**
   - 🌐 Facebook: **[https://www.facebook.com/sakhawat.sumon2](https://www.facebook.com/sakhawat.sumon2)**
3. Choose your license plan:
   - **Lifetime Commercial License** (Permanent license with free updates)
   - **Annual Subscription** (365 Days)
   - **Monthly Subscription / Evaluation** (30 Days)
4. You will receive an **Activation Key**. Paste it into the box and click **Activate License**.
5. The status will immediately turn green: **ACTIVE (Lifetime)**. All tools are unlocked and ready to use!

---

## 📞 Support & Inquiries

For sales, technical support, corporate training, or feature requests:
- **Architect & Author**: Sakhawat Hosen Sumon
- **Email**: [arch.sakhawat@gmail.com](mailto:arch.sakhawat@gmail.com)
- **Facebook**: [https://www.facebook.com/sakhawat.sumon2](https://www.facebook.com/sakhawat.sumon2)
- **YouTube Tutorials**: [https://www.youtube.com/@archsakhawat](https://www.youtube.com/@archsakhawat)
- **Location**: Dhaka, Bangladesh

---

### Copyright Notice
© 2026 Sakhawat Hosen Sumon. All Rights Reserved Worldwide.  
Rhino® is a registered trademark of Robert McNeel & Associates.
