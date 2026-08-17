# Python QR Code Generator

A lightweight Python project that generates scannable QR codes from links or plain text using `qrcode` and `Pillow`. Built and tested inside Jupyter Notebook.

## Features
- **High Error Correction**: Uses `ERROR_CORRECT_H` (~30% recovery) to ensure reliable scanning even if printed at small scales.
- **Customization Ready**: Supports custom matrix sizing, border margins, and background/foreground colors.
- **Inline Display**: Fully compatible with Jupyter Notebook for real-time visualization.

## Tech Stack
* **Language**: Python 3.x
* **Libraries**: 
  * `qrcode` — Encodes URLs and text into QR code matrices.
  * `Pillow` — Renders and exports matrices into image files (PNG, JPG, SVG).

## Prerequisites & Installation

To run this notebook, install the necessary dependencies using `pip`:

```bash
pip install qrcode[pil]
