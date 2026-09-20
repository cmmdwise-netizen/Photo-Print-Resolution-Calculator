# Photo-Print-Resolution-Calculator
This is a calculator to determine pixels to Inches/inches to pixels at a certain DPI.
## Features & Usage

### 1. Inches to Pixels Calculator
* **Purpose:** Helps you determine the exact pixel dimensions required when designing layouts, photo books, or prints at a specific physical size.
* **How to Use:** 
  * Switch between units (**Inches** or **Centimeters**) using the top navbar toggle.
  * Select a standard photo preset (e.g., $4\times6$, $8\times10$, $16\times20$, $24\times36$) or enter custom dimensions.
  * Adjust the target DPI slider if you are targeting web resolution ($72\text{ DPI}$), standard prints ($150\text{ DPI}$), or high-end gallery prints ($300\text{ DPI}$ to $600\text{ DPI}$).
  * Copy the exact pixel count or full specifications directly to your clipboard with a single click.

### 2. Resolution to Max Print Size Calculator
* **Purpose:** Analyzes your camera file's pixel grid or megapixel count to determine the maximum physical size you can print before quality degrades.
* **How to Use:**
  * Enter your image's pixel width and height, or click one of the quick camera presets (e.g., 12 MP, 24 MP, 45 MP, or Full HD).
  * The tool instantly breaks down your maximum print capabilities at $300\text{ DPI}$ (Gallery Standard), $150\text{ DPI}$ (Standard Wall Art), and $72\text{ DPI}$ (Large Format / Distance Viewing).
  * Copy the full analysis report to your clipboard for your records or lab notes.

---

## Reference Data: Common Camera Aspect Ratios & Full-Frame Sensor Specs

The calculator references standard full-frame sensor grids (such as a 45.7-megapixel sensor like an $8256 \times 5504$ layout) to establish native print size boundaries:

| Aspect Ratio | Pixel Dimensions (Large) | Max Print Size at 300 DPI | Common Photographic Use / Context |
| :--- | :--- | :--- | :--- |
| **3:2** | $8256 \times 5504$ | $27.5 \times 18.3\text{ in}$ | Standard full-frame sensor native ratio; classic landscape and fine art format. |
| **16:9** | $8256 \times 4640$ | $27.5 \times 15.5\text{ in}$ | Widescreen format, cinematic landscape crops, and digital displays. |
| **1:1** | $5504 \times 5504$ | $18.3 \times 18.3\text{ in}$ | Square art prints and artistic square compositions. |
| **5:4** | $6880 \times 5504$ | $22.9 \times 18.3\text{ in}$ | Traditional large-format print ratio (fits standard frames like $8\times10$, $16\times20$, and $24\times30$ with minimal cropping). |
| **DX Crop (1.5x)** | $5408 \times 3600$ | $18.0 \times 12.0\text{ in}$ | APS-C crop mode for extended reach while maintaining a standard 3:2 ratio. |

---

## Hosting & Deployment
This project is built as a single, self-contained `index.html` file with zero complex server dependencies, making it optimized for fast loading and deployment via **GitHub Pages** on a custom domain.
