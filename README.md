# Speed Booster Effective Aperture Calculator

Optical conversion formulas and reference calculations for filmmakers and photographers adapting full-frame lenses to crop-sensor cameras using focal reducers (Speed Boosters).

For the live interactive web tool, visit the official **[Speed Booster Calculator](https://speedboostercalculator.com/)**.

## The Math Behind Focal Reducers

When using a focal reducer (like a 0.71x Metabones or Viltrox adapter), both the focal length and the f-number (aperture) of the lens are reduced, resulting in a wider field of view and increased light transmission.

### Core Formulas

*   **Effective f-number (Aperture):** `Original f-number × Adapter Ratio`
*   **Effective Focal Length:** `Original focal length × Adapter Ratio`
*   **Full-Frame Equivalent Focal Length:** `(Original focal length × Adapter Ratio) × Sensor Crop Factor`
*   **Light Gain (Stops):** `-2 × log2(Adapter Ratio)`

### Worked Example (50mm f/1.8 on APS-C with 0.71x Speed Booster)

*   **Effective Focal Length:** `50mm × 0.71` = **35.5mm**
*   **Effective Aperture:** `f/1.8 × 0.71` = **f/1.28**
*   **Full-Frame Equivalent Field of View:** `(50mm × 0.71) × 1.53` = **54.31mm**
*   **Light Transmission Gained:** `-2 × log2(0.71)` = **+0.98 stops** (approx. 1 full stop)

## Common Sensor Crop Factors
*   **Micro Four Thirds (MFT):** 2.0x
*   **Canon APS-C:** 1.6x
*   **Sony/Nikon/Fuji APS-C:** 1.5x to 1.53x
*   **Super 35:** ~1.37x to 1.5x

---
*Developed and maintained by [Th3_ahmad](https://github.com/th3ahmad) / [Speed Booster Calculator](https://speedboostercalculator.com/).*
