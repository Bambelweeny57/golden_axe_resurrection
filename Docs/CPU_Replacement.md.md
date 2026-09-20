# 🧠 CPU Replacement Guide  
### Replacing the Encrypted Sega MC68000 Module

The original Golden Axe arcade PCB uses a Hitachi/Sega MC68000 CPU with an attached battery-backed encryption module.  
When the battery dies, the CPU loses its decryption key and the board becomes non-functional.

This guide explains how to safely remove the encrypted CPU and install a standard MC68000-10.

---

## 🔧 Required Tools & Parts

- Temperature-controlled soldering iron  
- Desoldering pump or hot-air station  
- Replacement **MC68000-10** CPU  
- Isopropyl alcohol (IPA)  
- Fine-tip tweezers  
- Flux

---

## 🪛 Removal Procedure

1. **Power off and discharge the board**  
   Ensure no residual voltage is present.

2. **Identify the CPU module**  
   It is a large DIP package with a smaller protection module bonded on top.

3. **Desolder the CPU pins**  
   Apply flux and heat each pin.  
   Use a pump or hot air to free the package.

4. **Lift the CPU carefully**  
   Avoid damaging surrounding traces.

5. **Clean the pads**  
   Remove old solder and inspect for lifted pads.

---

## 🧩 Installing the New CPU

1. Align the **MC68000-10** with the original footprint.  
2. Solder opposite corners first to anchor the chip.  
3. Solder remaining pins with light flux.  
4. Inspect for bridges using magnification.  
5. Clean with IPA.

---

## ✔️ Verification

After installing the new CPU:

- Check continuity on all data and address lines  
- Ensure no shorts to ground  
- Proceed to ROM replacement

Your board is now free from the dead encryption module.
<img src="https://github.com/Bambelweeny57/golden_axe_resurrection/blob/main/Images/IMG_2152.jpeg" width="400">