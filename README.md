# Rifaz Ventoy Theme

<p align="center">
  <i>Modern glassmorphism boot theme with bold, vibrant visuals</i><br>
</p>

---

## ✨ Overview

**Rifaz Ventoy Theme** delivers a **clean, modern boot interface** using glassmorphism design and strong visual contrast.


---

## 🎨 Theme Highlights

* **Glassmorphism UI**
  Smooth transparent container with blur effect

* **Bold Default Design**
  Rich **red background** with high contrast elements

* **Multiple Variants**
  Includes:

  * 🔴 Red (default)
  * ⚫ Black
  * 🔵 Blue

* **Modern Typography**
  Clean and highly readable interface

* **Refined Layout**
  Balanced spacing and centered structure for clarity

* **Extensive Icon Support**
  Designed to visually integrate with multiple boot entries and tools

---

## 📂 Repository Structure

```text
rifaz-ventoy-theme/
├── theme/
│   └── rifaz/
│       ├── theme.txt
│       ├── background.png
│       ├── poppins.pf2
│       ├── icons/
│       └── variants/
└── README.md
```

---

## 🛠 Installation Guide

### ✅ Method 1: VentoyPlugson (Recommended)

1. Create folder in USB:

   ```
   /ventoy/
   ```

2. Copy theme:

   ```
   /ventoy/theme/rifaz/
   ```

3. Run:

   ```
   VentoyPlugson.exe
   ```

4. Open **Theme Plugin**

5. Add:

   ```
   /ventoy/theme/rifaz/theme.txt
   ```

6. Save changes

---

### ⚙️ Method 2: Manual Setup

1. Place theme in:

   ```
   /ventoy/theme/rifaz/
   ```

2. Open or create:

   ```
   /ventoy/ventoy.json
   ```

3. Add:

```json
{
    "theme": {
        "file": "/ventoy/theme/rifaz/theme.txt"
    }
}
```

---

## 🎨 Switching Variants

1. Go to:

   ```
   /ventoy/theme/rifaz/variants/
   ```

2. Choose:

   * red / black / blue background

3. Replace:

   ```
   background.png
   ```

---

## 🧾 Credits

* **Inspiration**
  sleek-themes by **sandesh236**

* **Design & Customization**
  Rifaz

* **Font**
  Poppins — Indian Type Foundry

---

## 📜 License

**MIT License**
You can use/modify it but please give credits 😁

---

## ⚠️ Notes

* Optimized for standard widescreen displays
* Minor differences may appear on unusual resolutions

---
