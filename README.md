# Parametric Battery Case Generator

A fully parametric battery case system designed in Fusion 360. Configurable for multiple cylindrical battery sizes, with optional magnet-fit lids.

## ✅ Features
- Supports common cylindrical cells (18650, 21700, LTO, etc.)
- Configurable battery count (rows/columns)
- Optional magnet retention
- Wall thickness, fit tolerance, and edge rounding all user-controlled
- Clean FDM-friendly geometry (no supports required)

## 🛠 How to Customize

Open the included `.f3d` file in Fusion 360. Modify only the **editable parameters** listed below.

### 🔧 Editable Parameters

| Parameter              | Purpose                              |
|------------------------|--------------------------------------|
| `BatteryLength`        | Battery length in mm                 |
| `BatteryDiameter`      | Battery diameter in mm               |
| `BatteryRow`           | Number of batteries front-to-back    |
| `BatteryCol`           | Number of batteries side-to-side     |
| `WallThickness`        | Outer and bottom wall thickness      |
| `MagnetDiameter`       | Diameter of magnets used (optional)  |
| `MagnetDepth`          | Depth of magnet holes                |
| `lidOffset`            | Tolerance for lid fit (PETG = 0.5mm) |
| `BatteryDepthInBase`   | % of battery housed in base enclosure|
| `BatteryDepthInLid`    | % of battery enclosed by lid         |
| `EdgeRounding`         | Radius of visual edge rounding       |

### 🚫 Do Not Modify

These are **formula-driven** parameters. Changing them will break the model.

| Parameter            | Reason                                  |
|----------------------|------------------------------------------|
| `CaseHeight`         | Derived from battery/base dimensions     |
| `CaseLidHeight`      | Derived from battery/lid dimensions      |
| `CaseDepth`          | Auto-calculated from layout and spacing  |
| `CaseWidth`          | Same as above                           |
| `MagnetPadOffset`    | Depends on magnet size, wall, and offset |

## 📦 Included Files

- Fusion 360 source: `.f3d`
- STL exports for common sizes
- `param_map.png` for quick reference

## 📩 Need a Custom Size?

Message me directly — I’ll generate the STL for you or help you tweak the parameters.
