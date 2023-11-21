<!-- Copyright: The MIT License, 2023 Jonah Yolles-Murphy for the UMass Amherst M5 Maskerspace -->

# M5 Open Labels

M5 Open Labels is the HTML, CSS, and Related Documentation used for generating bin labels for the [UMass Amherst M5 Makerspace](https://www.umassamherstm5.org/).

M5 Labels are generated as HTML files using using the structure and CSS provided in this repository (see : ./examples/format.html). The HTML files are printed using a browser (e.g. Chrome) and cut to size.

## Eample Label


## Design and Use

As of v0.4.0 (2023nov20), the labels are designed to be printed on 8.5" x 11" paper and cut to size; best results have been achieved with Cardstock.


### Attaching to M5 Parts Wall Bins (CMST40730 Drawers)
This is intedned to be attached:
- as one peice of paper with the QR and Left panels on the left side of the drawers.
- with 1" wide scotch magic tape (frosty scoth tape)

1. Bend then crease the label along vertical line to the right of QR panel (so the text is facing on both sides of the bend).
2. It should be able to be attached with three pieces of tape 1":
  - `1x ~4 inch` lenth piece of tape
    - place horizontally a the 1" edge of the tape starting from inside left edge of the QR code.
    - Wrap rightwards, covering the QR Code and the front panel, before adhereing to right face of the bin.
  - `2x ~3 inch` lenth pieces of tape
    - place both vertically, with...
      -  with a long edge of one center/aligned with the leftmost cut edge of the label.
      -  the a long edge of the other along the left of the vertical line between the QR and Left panels. 
    - The extra ~1 inch lengths of tape should be wrapped up and over the top lip of the bin and adhere along the bottom of the bin.


## Bin Compatibility
Each label is 7" by 1" and was deisnged to fit on: 
  - **Craftsman CMST40730** (M5 Parts Wall Bins) – See above
  - **Sterilite Mini Storage Box 19698606** – with the QR and title panels on the side of the box with a handle. It may be easier to attache as two peice: if so, cut the labels along the line to the left of the QR code. 
  - **Sterilite Large Storage Box 19638606** – with the whole label across the front/back of the box.
    (though, please always print two and put one on each side 😅).
  - The other Sterilite Storage Boxes in the same family

Of course theses can be used with other bins, but the QR code may not be in the most convenient location.

## Browser Compatibliity
As of v0.4.0 (2023nov20), the labels have been tested on the following browsers:
- **Google Chrome:** Version 119 (Official Build)
- **Safari (on macOS):**  Version: 16.6 (1861)


## Known issues 
- [x] \[#1\] RESOLVED(2023nov20) These is a bug on safari where the title border cannot be smaller than 3px; Please use chrome if you're enableing any of `--title-border-left`, `--title-border-right`, or `--title-border-bottom`
  
## Notes
The structure of this repository assists in the use/generation of M5 Open Labels by my be adjusted in the future.
- The link to raw files in this repository by be used to import CSS when generating labels.


## Supported Features
- TODO(@TG-Techie) see ./examples/format.html (ex: label-list tag, label-version-format tag, item-title tag, etc.)