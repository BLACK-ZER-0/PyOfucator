<p align="center">                                                                       
 <img src="https://i.postimg.cc/ncnQbbvg/1000260033.jpg" width="600"/>         
</p>                                                                                                                         <h1 align="center">🐍 PyOfucator </h1>                            <p align="center">                                         🇧🇩 Developed by <b>BLACK ZERO</b><br>                                                                   📆 Year: 2025                                                                         </p>


**PyOfucator** is a Python **code obfuscation tool** that encrypts and hides your Python scripts using multiple encoding techniques.
This makes reverse engineering your code much harder.

---

## ✨ Features

* Beautiful **Rich + PyFiglet** UI (Colorful Banner, Table, Panels)
* Multiple encoding methods:

  * **Marshal**
  * **Zlib**
  * **Base16, Base32, Base64**
  * **Combination encodes (Marshal+Zlib+BaseX)**
* Advanced Fake Encode Modes:

  * Fake **Cython Encode**
  * Fake **PyInstaller Encode**
  * Real Cython-Style Encode 
* Custom encode count (multi-layer encoding)
* Displays encoded file size
* Compatible with **Python 3.11**

---

## 📦 Requirements

* Python **3.10+** (tested on 3.11)
* Modules:

  * `rich`
  * `pyfiglet`

Install dependencies:

```bash
pip install rich pyfiglet
```

---

## 🚀 Usage

Run:

```bash
pkg update && pkg upgrade
pkg install git -y
pkg install python -y
pkg install python3 -y
pip install pyfiglet
pip install rich 
termux-setup-storage -y
git clone https://github.com/BLACK-ZER-0/PyOfucator.git
cd PyOfucator
chmod +x *
python3 pyofucator.py
```
For Just Python (not python3) use :
```bash
python pyofucator.py
```
### Steps:

1. Banner and **Main Menu** will appear.
2. Select encoding method (1–18).
3. Enter encode count (how many times to obfuscate).
4. Enter the Python file name (`.py`) to obfuscate.
5. Encoded file will be saved as `[filename]_enc.py`.

---

## 🧩 Example

Suppose you have a file `script.py`:


➡ Choose option → `9 (Marshal + Zlib)`
➡ Encode Count → `3`
➡ File Name → `script.py`

Output:

```
[-] Successfully Encrypted script.py
[-] Saved as script_enc.py
[-] Encoded File Size : 12.3 KB
```

---

## 📖 Menu Options

| No | Method                          | Power       |
| -- | ------------------------------- | ----------- |
| 01 | Encode Marshal                  | Medium      |
| 02 | Encode Zlib                     | Medium      |
| 03 | Encode Base16                   | Weak        |
| 04 | Encode Base32                   | Weak        |
| 05 | Encode Base64                   | Weak        |
| 06 | Encode Zlib + Base16            | Strong      |
| 07 | Encode Zlib + Base32            | Strong      |
| 08 | Encode Zlib + Base64            | Strong      |
| 09 | Encode Marshal + Zlib           | Strong      |
| 10 | Encode Marshal + Base16         | Strong      |
| 11 | Encode Marshal + Base32         | Strong      |
| 12 | Encode Marshal + Base64         | Strong      |
| 13 | Encode Marshal + Zlib + Base16  | Very Strong |
| 14 | Encode Marshal + Zlib + Base32  | Very Strong |
| 15 | Encode Marshal + Zlib + Base64  | Very Strong |
| 16 | Fake Cython Encode              | Ultra+      |
| 17 | Fake PyInstaller Encode         | Ultra++     |
| 18 | Real Cython Style Encode        | Alpha       |
| 20 | Exit                            | -           |

---
## 📷 TOOL PICTURE
![screenshot](https://i.postimg.cc/zfnYCMVS/1000260035.jpg)

## ⚠️ Disclaimer

This tool is made **for educational purposes only**.
Use it to protect your own projects.
Do **not** use it for stealing or malicious activities — that is illegal.

---

✍️ Developer: [BLACK ZERO](https://black-zero.vercel.app/)

👥 Team: **BANGLADESH Cyber Squad**

---

