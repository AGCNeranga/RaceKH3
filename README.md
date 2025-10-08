# RaceKH

A secure web tool to process and highlight Harness Race data. Supports multiple file uploads, automatic K/H marking for horses, proper formatting of race details, and a smooth background slideshow. Includes password protection and export functionality for processed race files.

---

## Features

- Password-protected access for secure use.
- Upload up to 10 race text files and process them individually.
- Automatic K/H marking for the top 2 horses in each race.
- Cleans unwanted tags like `<&te>` and `<&tb(...) *C>`.
- Adds `<v9.00> <e0>` to `@Cour:` lines automatically.
- Correctly formats `@Race:` lines with proper spacing between code, time, and title.
- Highlight K/H horses in a separate popup window.
- Export processed race files as `.txt` with `_KH` suffix.
- Smooth background slideshow for a visually appealing interface.
- Clear All button to reset inputs and outputs.

---

## Installation

```bash
git clone https://github.com/yourusername/Harness-Race-Marker.git
