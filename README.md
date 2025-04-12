# 🛡️ Malware Detection GUI

A Python-based malware detection GUI using `tkinter` for interactive full scans, location-specific scans, update handling, and configuration settings.

---

## 🖼️ Description

This project provides a visually appealing and functional GUI menu to manage different components of a malware detection system. The user can initiate full system scans, location-based scans, update antivirus definitions, and change settings – all from a single interface.

---

## 🧩 Features

- 🔍 **Full Scan**: Scan the entire system for malware
- 📁 **Location Scan**: Custom scan specific folders or files
- 🔄 **Update Definitions**: Keep the antivirus updated
- ⚙️ **Settings Panel**: Manage antivirus settings
- 🖼️ Custom image background and hover effects

---

## 🛠️ Technologies Used

- **Python**
- **tkinter**: GUI framework
- **Pillow (PIL)**: Image loading and display
- **Custom Modules**:
  - `AntivirusFrontend`
  - `FullScan`
  - `Settings`
  - `Updates`

---

## 📂 File Structure

```
MalwareDetectionGUI/
├── main.py                  # GUI main interface
├── abc.jpg                  # Background image
├── antivirasFrontend.py     # Location scan logic
├── fullScann.py             # Full scan logic
├── settings.py              # Settings window
├── updates.py               # Update checker
└── README.md                # Project documentation
```

---

## ▶️ How to Run

### Step 1: Install Dependencies

```bash
pip install pillow
```

### Step 2: Run the GUI

```bash
python main.py
```

Make sure `abc.jpg` and other Python modules are in the same directory.

---

## 🧠 Notes

- This is a GUI frontend. The actual antivirus logic should be implemented in the corresponding modules:  
  - `AntivirusFrontend` (for custom location scan)  
  - `FullScan` (for full system scanning)  
  - `Settings` and `Updates` for user preferences and software updates.

---

## 📸 Preview

 ![Main Interface](https://github.com/Yash-Raj-96/Malicious-URL-Detection/blob/main/a.jpg?raw=true) 
 ![Scan Options](https://github.com/Yash-Raj-96/Malicious-URL-Detection/blob/main/b.jpg?raw=true) 
 ![Settings and Updates](https://github.com/Yash-Raj-96/Malicious-URL-Detection/blob/main/c.jpg?raw=true) 

---

## 🙋 Author

### 👨‍💻 Made with ❤️ by [**Yash Raj**](https://github.com/Yash-Raj-96)  
[![GitHub Follow](https://img.shields.io/github/followers/Yash-Raj-96?label=Follow%20Me&style=social)](https://github.com/Yash-Raj-96)


---

## ⚖️ License

MIT License
