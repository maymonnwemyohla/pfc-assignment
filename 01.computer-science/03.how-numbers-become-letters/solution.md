# 📝 Solution: How Numbers Become Letters?

**Student Name:** May Mon Nwe Myo Hla
**Date:** 2026-08-06

---

### Task 1: Concept Questions

#### (a) How Computers Display Characters
* **Answer:**
  > Computers display characters by turning typed keys into numbers using codes like ASCII or Unicode, matching those numbers to visual shapes in a font file and lighting up tiny screen dots called pixels to draw the final image.

#### (b) ASCII vs. Unicode
* **Main Difference:** The main difference is scope and size: ASCII is a small, 7 bit standard limited to 128 English letters, numbers, and basic symbols, while Unicode is a universal standard supporting over 149,000 characters from global languages, scripts and emojis.
* **Why Unicode was created:** Unicode was created to replace hundreds of conflicting,limited local text codes with one universal system.

---

### Task 2: ASCII & Character Encoding

#### (a) ASCII Limitations
* **Bits per character in ASCII:** 7 Bits
* **Maximum unique characters in ASCII:** 128 characters

#### (b) Encoding the word "CAT"
* **'C':** Decimal = `67` | 8-bit Binary = `01000011`
* **'A':** Decimal = `65` | 8-bit Binary = `01000001`
* **'T':** Decimal = `84` | 8-bit Binary = `01010100`

---

### Task 3: Text Storage & Byte Calculation

#### (a) Memory in Bytes for `"Hello, World!"`
* **Answer:** 13 Bytes

#### (b) Total Bits
* **Calculation:** 13 × 8
* **Answer:** 104 Bits

#### (c) Multi-byte Characters (Myanmar Script & Emojis)
* **Answer:**
  > UTF-8 uses multiple bytes for characters outside the ASCII range because it needs a way to store over one million symbols while keeping old single-byte ASCII files safe.

---