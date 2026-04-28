# CiderPress 
<img width="256" height="256" alt="CiderPress" src="https://github.com/user-attachments/assets/b3780a71-5151-474b-adab-5f270db34c70" />

### HEIC/HEIF → JPG/PNG Converter for Windows

CiderPress is a fast, reliable, drag‑and‑drop converter for **HEIC/HEIF** images.  
It uses **FFmpeg** for decoding, **ExifTool** for full metadata preservation, and includes a clean WIC fallback when FFmpeg isn’t available.

Simple UI. Accurate results. No nonsense.

CiderPress exists because Windows still doesn’t handle HEIC/HEIF gracefully.
iPhones produce HEIC by default, but opening, previewing, or converting those
files on a PC is often slow, inconsistent, or locked behind paid codecs and
clunky web tools.

This app is for anyone who needs a dependable, offline, privacy‑respecting way
to convert HEIC photos — photographers, editors, archivists, IT staff, or
everyday users who just want their pictures in a format everything supports.

No ads, no telemetry, no installers, no surprises. Just a small, portable tool
that does the job properly.

<img width="901" height="424" alt="screenshot01" src="https://github.com/user-attachments/assets/bd646934-1718-4558-b1cf-074dd1af9f00" />

---

## ⭐ Features

### **✔ Drag‑and‑drop batch conversion**
Drop files or entire folders directly into the list.  
CiderPress automatically filters supported formats and avoids duplicates.

### **✔ JPG or PNG output**
- JPG with adjustable quality  
- PNG with adjustable compression  

### **✔ Fast or Full metadata modes**
- **Fast Mode:** FFmpeg‑only, partial metadata  
- **Full Mode:** FFmpeg + ExifTool, maximum metadata retention  
- Automatic fallback if ExifTool isn’t found

### **✔ Timestamp preservation**
Optionally copy creation/modification timestamps to output files.

### **✔ Custom output folder**
Save converted files next to the originals or route them to a dedicated folder.

### **✔ Multi‑threaded FFmpeg**
Enable multi‑threading for faster batch conversions on multi‑core CPUs.

### **✔ Live preview**
Displays a real‑time preview of the selected source image using FFmpeg, with WIC fallback.

### **✔ Clear progress tracking**
Status bar shows:
- File count  
- Pipeline mode  
- Conversion state  
- **Working (X of Y)** progress indicator  

### **✔ Safe Stop button**
Stop conversions at any time.  
CiderPress cleanly terminates FFmpeg and ExifTool without leaving orphaned processes.

### **✔ Quiet Mode**
When starting a conversion, CiderPress warns that Settings are disabled during processing.  
Choose **Quiet** once, and the warning is permanently suppressed until the INI is reset.

---

## 📦 Requirements

- **Windows 10/11**
- **FFmpeg** (recommended)  
  - Place `ffmpeg.exe` next to the app or ensure it’s in PATH.
- **ExifTool** (optional, for full metadata mode)  
  - Place `exiftool.exe` next to the app or in PATH.

CiderPress automatically detects both tools.

---

## 🧳 Portable by Design

CiderPress is a fully portable Windows application — no installation, no registry
entries, and no system modifications. Just extract the ZIP and run
`CiderPress.exe`.

Portability benefits include:

• No installer required  
• No admin rights needed  
• No registry usage  
• No files written outside the app folder  
• Works from USB drives, network shares, or cloud folders  
• Self‑contained settings (INI stored next to the EXE)  
• FFmpeg and ExifTool auto‑detected when placed in the same folder  

This makes CiderPress ideal for portable toolkits, restricted environments,
temporary workstations, and privacy‑focused users. Everything stays in its own
folder, and it runs anywhere.

---

## 🔒 Privacy‑Focused

CiderPress is built with a strict privacy‑first design. The app never sends data
anywhere, never connects to the internet, and never collects analytics or usage
information. All processing happens locally on your machine.

• No telemetry  
• No background network requests  
• No cloud dependencies  
• No hidden logs or data collection  
• All settings stored locally in a simple INI file  
• FFmpeg and ExifTool run entirely offline  

Your images stay on your system, your metadata stays private, and nothing leaves
your computer — ever.

---

## 🚀 How to Use

1. Launch CiderPress  
2. Drag HEIC/HEIF files or folders into the list  
3. Choose JPG or PNG  
4. Adjust quality/compression if desired  
5. Click **Convert**  
6. Watch progress in the status bar  
7. Click **Stop** anytime to cancel safely  

Converted files appear in the source folder or your custom output folder.

---

## ⚙ Settings Overview

### **Decoder**
- Auto  
- FFmpeg  
- WIC (no metadata)

### **Output Options**
- Custom output folder  
- Overwrite existing files  
- Preserve timestamps  
- Append suffix (e.g., `_converted`)  

### **Metadata**
- Fast (FFmpeg only)  
- Full (FFmpeg + ExifTool)

### **Error Handling**
- Skip failed files  
- Stop on first error  

### **Appearance**
- Windows  
- Dark  
- Light  
- Aqua  

---

## 📝 Logging & Diagnostics

Enable diagnostic logging to generate a detailed `CiderPress.log` file.  
Useful for debugging FFmpeg/ExifTool behavior or reporting issues.

---

## 📄 Licensing

CiderPress uses a **custom dual‑license model**:

### **✔ Free for Personal Use**
You may use CiderPress at no cost for:
- Home use  
- Hobby projects  
- Personal photo management  
- Student or educational use  
- Non‑profit individual use  

### **✔ Commercial Use Requires a One‑Time $10 License**
Commercial use includes:
- Business or organizational use  
- Use by employees as part of their job  
- Professional photography, real estate, insurance, etc.  
- Any revenue‑generating workflow  

Commercial licenses can be purchased here:  
**https://ko-fi.com/superevil**

See `License.txt` for full terms.

---

## ❤️ Support the Project

If you find CiderPress useful, consider supporting development:  
**https://ko-fi.com/superevil**

---

## 🪟 Screenshots

Below is a preview of the CiderPress interface, showing the drag‑and‑drop file list,
conversion options, live preview panel, and progress display.

<img width="901" height="424" alt="screenshot01" src="https://github.com/user-attachments/assets/cf209fea-663b-4dc2-afc5-f6b8e446f5f1" />
<img width="921" height="403" alt="screenshot03" src="https://github.com/user-attachments/assets/b6b17495-61ad-451b-a801-e0313446e421" />
<img width="921" height="403" alt="screenshot02" src="https://github.com/user-attachments/assets/40e49fcf-86ef-49c7-8c85-452d6a6abe1e" />
<img width="921" height="477" alt="screenshot04" src="https://github.com/user-attachments/assets/5e0b8c61-caa9-4a99-9e81-3e6ccfbeb1e4" />


CiderPress is designed to stay clean, compact, and predictable — everything you need
for batch HEIC/HEIF conversion without clutter or noise.


## 🙌 Credits

- **FFmpeg** — https://ffmpeg.org  
- **ExifTool** — https://exiftool.org  
- **Delphi VCL** for the UI framework  

---

CiderPress is built to be fast, predictable, and pleasant to use — a small utility that does one job extremely well.
