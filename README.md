# GLF-Amara

## About
This typeface is a striking, high-contrast display serif that marries classical elegance with modern, bold proportions. It features exaggerated weight transitions, juxtaposing ultra-thick vertical stems with razor-thin horizontal serifs and fine hairlines, giving it a dramatic, architectural presence on the page.

## Building the Fonts Manually

If you prefer to compile the font files locally on your machine from the raw source data, follow these steps:

### Prerequisites
Make sure you have **Python 3.10 or higher** installed on your system.

### Installation
Open your terminal and install the required font engineering tools via pip:
```bash
pip install fontmake glyphsLib fontbakery[googlefonts] gftools
```

### Build Instructions
Run the following command to generate desktop-ready OpenType and TrueType fonts:
```bash
# Create destination directories
mkdir -p fonts/ttf fonts/otf

# Compile the .glyphs source file
fontmake -g Sources/GLF_Amara.glyphs -o ttf --output-dir fonts/ttf/
fontmake -g Sources/GLF_Amara.glyphs -o otf --output-dir fonts/otf/
```
The compiled files will appear inside the newly created `fonts/` directory.

![Alt Text](GLF-Amara.png)

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
https://openfontlicense.org

## Contributors
Sidiq Kamal Nurmawan <sidiq.nurmawan@gmail.com>
Erwin Wirianata <wirianata.erwin@gmail.com>
