# Cycloid Drive V1 (3D Printed / Machined)

A compact **cycloidal gearbox** design intended for **3D printing and/or machining**, built around an eccentric input and a cam-roller ring. This version targets a **~20:1 reduction** and uses **21 cam rollers**. fileciteturn4file0L9-L12

<p align="center">
  <img src="https://user-images.githubusercontent.com/5108887/211717686-65bd38b3-96a7-471e-b133-338ed94d52c1.PNG" width="520" alt="Cycloid Drive V1" />
</p>

---

## Quick specs

- **Type:** Cycloidal reducer (dual-disk, out-of-phase) fileciteturn4file0L24-L26  
- **Target reduction:** **20:1** fileciteturn4file0L11-L11  
- **Cam rollers:** **21** fileciteturn4file0L12-L12  
- **Build style:** **3D printed / machined** (not the acrylic version) fileciteturn4file0L9-L9  

---

## What’s included

- CAD for the drive (the STLs are exported from the SolidWorks CAD) fileciteturn4file0L7-L7  
- Part-numbered components + full bill of materials table fileciteturn4file0L18-L41  
- Preview images of the cycloidal cam + disk geometry fileciteturn4file0L14-L16  

<p align="center">
  <img src="https://user-images.githubusercontent.com/5108887/211712124-5d160e18-ea3c-4a23-bca7-3478abd2f5b9.png" width="520" alt="Cycloidal cam and disk preview" />
</p>

---

## Important printing note

The STLs were exported from the SolidWorks CAD file and **may not match your 3D printer’s tolerances**, so **print at your own risk**. fileciteturn4file0L7-L7  
If you’re getting binding or backlash, the usual fix is to adjust clearances (bearing pockets, dowel pin holes, cam roller fits) and re-export STLs for your machine/material.

---

## Bill of Materials (BOM)

| ITEM NO. | PART NUMBER | DESCRIPTION | QTY. |
|:--:|:--|:--|:--:|
| 1 | LTRPT-0001-0001-00 | Eccentric Bottom Bearing Housing | 1 |
| 2 | LTRPT-0001-0002-00 | Eccentric Shaft Coupler | 1 |
| 3 | LTRPT-0001-0003-00 | Cycloid Disk 20:1 | 1 |
| 4 | LTRPT-0001-0004-00 | Cycloid Disk 20:1 Out of Phase | 1 |
| 5 | LTRPT-0001-0005-00 | Inner Ring Base | 1 |
| 6 | LTRPT-0001-0006-00 | Output Disk | 1 |
| 7 | LTRPT-0001-0007-00 | Eccentric Shaft Top | 1 |
| 8 | LTRPT-0001-0008-00 | Eccentric Shaft Bottom | 1 |
| 9 | LTRPT-0001-0006-01 | Output Disk Resin | 1 |
| 10 | LTRPT-0001-0009-00 | Eccentric Bottom Bearing Housing | 1 |
| 11 | LTRPT-0001-0010-01 | Motor Mounting Base Plate | 1 |
| 12 | LTRPT-0001-0011-00 |  | 1 |
| 13 | LTRPT-0001-0012-00 | Motor Mounting Base Plate | 1 |
| 14 | GARTT ML5008 330KV | GARTT ML5008 330KV | 1 |
| 15 | 6656K229 | Ultra-Thin Ball Bearing | 2 |
| 16 | 5x25mm Dowel Pin | 5mm x 25mm Dowel Pin | 3 |
| 17 | MR95ZZ |  | 24 |
| 18 | 91290A252_AlloySteel Socket HeadScrew | Alloy Steel Socket Head Screw | 3 |
| 19 | 6656K182 | Ultra-Thin Ball Bearing | 4 |
| 20 | 91290A130_Black-Oxide Alloy SteelSocket Head Screw | Black-Oxide Alloy Steel Socket Head Screw | 2 |

---

## Assembly overview (high level)

> This section is intentionally “high level” because exact fits depend heavily on printer tolerances and any machining you do.

1. **Prepare rollers + bearings**  
   Press-fit bearings and confirm smooth rolling (no binding).

2. **Build the eccentric stack**  
   Assemble the eccentric shaft components and bearing housings.

3. **Install the cycloidal disks**  
   Mount the **two 20:1 disks** with the **out-of-phase** disk aligned correctly. fileciteturn4file0L24-L26

4. **Add the cam roller ring**  
   Place and secure the roller ring (21 rollers). fileciteturn4file0L12-L12

5. **Attach the output disk + motor mount**  
   Finish the output stage, then mount the motor.

---

## Suggested repo layout (optional)

If you’re publishing this as a standalone repo, a clean structure is:

```
/CAD        (SolidWorks source files, STEP exports)
/STL        (printable STLs, versioned by tolerance)
/BOM        (CSV + sourcing notes)
/images     (renders + build photos)
/docs       (assembly notes + revisions)
```

---

## License

Add a `LICENSE` file to clarify reuse/redistribution.

---

## Credits

Project label: **LTR_01** fileciteturn4file0L1-L2
