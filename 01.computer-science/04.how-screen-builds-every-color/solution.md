# 📝 Assignment 04: How Screen Builds Every Color?

**Student Name:** May Mon Nwe Myo Hla
**Date:** 2026-08-07

---

### Task 1. Concept Questions
* **(a)** Explain briefly how a computer screen creates various colors (like Yellow or White) using only **Red, Green, and Blue** light.
  > A monitor or TV screen generates three colors of light (red, green and blue) the different colors we see are due to different combinations and intensities of these three primary colors.

* **(b)** Why does standard digital color use **8 bits (1 byte) per color channel** (R, G, B)? How many total color channels are in a standard pixel, and how many total bits does a full RGB pixel use?
  > 8 bits are used because it gives 256 different shades for each color, which is enough for the human eye. There are 3 colors channels(Red, Green, Blue) so a full pixel uses 24 bits in total(8 bits * 3 channels).

### Task 2. RGB Values & Hex Codes
* **(a)** In an 8-bit per channel RGB system, each color channel ranges from `0` to `255`. State the RGB values for the following colors:
  * **Pure Red:** `RGB( 255, 0, 0 )`
  * **Pure White:** `RGB( 255, 255, 255 )`
  * **Pure Black:** `RGB( 0, 0, 0 )`

* **(b)** Hexadecimal (Hex) color codes convert RGB values into base-16 representations. Express the RGB value `RGB(255, 0, 0)` as a **6-digit Hex Code** (e.g., `#FFFFFF`).
  > #FF0000

### Task 3. Resolution & Image Memory Calculation
Consider an uncompressed digital photo with a resolution of **1920 × 1080 pixels** (Full HD) using **24-bit True Color** (3 Bytes per pixel):

* **(a)** How many total **pixels** are on this screen/image?
  > There are 2,073,600 pixels in total (1920 * 1080).

* **(b)** Calculate the total raw file size in **Bytes**. *(Show your calculation step)*
  > Total pixels =  2,073,600 -> file size in Bytes = 2,073,600 * 3 = 6,220,800 Bytes
  
* **(c)** Convert the total size into **Megabytes (MB)**. *(Note: 1 MB = 1,024 × 1,024 Bytes or 1,048,576 Bytes)*
  > Total size into MB = 6,220,800 / 1,048,576 = 5.93 MB

---