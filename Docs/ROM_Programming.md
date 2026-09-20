# 💾 ROM Programming Guide  
### Creating Resurrection ROMs for Golden Axe

Golden Axe uses two encrypted program ROMs: **12388A1** and **12389A2**.  
These must be replaced with unencrypted Resurrection ROMs programmed onto M27C2001 EPROMs.

---

## 📦 Required Items

- **M27C2001** EPROMs (2x)  
- EPROM programmer (Dataman, TL866, etc.)  
- Resurrection ROM files from `/ROMs`  
- UV eraser (if reusing EPROMs)

---

## 🔥 EPROM Preparation

1. **Erase EPROMs**  
   Place under UV light for 10–20 minutes.

2. **Verify blank state**  
   Programmer should report all bytes as `0xFF`.

---

## 📝 Programming Steps

1. Load the **A1 Resurrection ROM** into your programmer software.  
2. Select device type: **M27C2001**  
3. Program the EPROM  
4. Verify the written data  
5. Repeat for **A2 Resurrection ROM**

---

## 🧪 Testing

Once programmed:

- Insert A1 and A2 into their original sockets  
- Ensure correct orientation (notch alignment)  
- Power the board

If the CPU has been replaced, the board should now boot normally.

---

## 🛠️ Troubleshooting

- **Garbage screen** → Check ROM orientation  
- **No boot** → Verify CPU replacement  
- **Random resets** → Clean ROM pins and reseat

<img src="https://github.com/Bambelweeny57/golden_axe_resurrection/blob/main/Images/IMG_2153.jpeg" width="400">