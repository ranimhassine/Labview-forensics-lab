# 🔍 **Digital Forensics Toolkit**

![GitHub repo size](https://img.shields.io/github/repo-size/ranimhassine/Labview-forensics-lab)
![GitHub contributors](https://img.shields.io/github/contributors/ranimhassine/Labview-forensics-lab)
![GitHub stars](https://img.shields.io/github/stars/ranimhassine/Labview-forensics-lab?style=social)
![GitHub forks](https://img.shields.io/github/forks/ranimhassine/Labview-forensics-lab?style=social)

> **"Empowering digital investigations with an intuitive, all-in-one solution."**

The **Digital Forensics Toolkit** is a comprehensive application built using **LabVIEW**, tailored for digital investigators, IT professionals, and students. Analyze files, generate and verify MD5 hashes, and document findings—all in a seamless, interactive environment. 🚀
NB: download all the VIs before using the UI

---

## 📌 **Key Features**

1. **File Selection (File Handler)**  
   - **Single File Mode**: Select a single file to analyze.  
   - **Batch Mode**: Select an entire directory for batch processing.  

2. **Hash Generation (Hash Generator)**  
   - Automatically compute the **MD5 hash** of selected files.  

3. **Hash Comparison (Hash Verifier)**  
   - Compare generated hashes with reference hashes to verify file integrity.  
   - **Results Display**: Clearly shows if files are a **"Match"** or have been **"Tampered"**.

4. **Logging Evidence Metadata (Logger)**  
   - Save analysis details, including:  
     - **File Name**  
     - **File Size**  
     - **Timestamp**  
     - **MD5 Hash**  
   - Output formats:
     - **CSV File**: For quick access.
     - **SQLite Database**: For scalable storage.

5. **User Interface (UI)**  
   - Intuitive **Front Panel** with:  
     - File selection controls.  
     - Buttons for hash generation, comparison, and logging.  
     - Display areas for metadata and results.

6. **Report Generation**  
   - Generate detailed forensic reports with:  
     - File metadata.  
     - Hash values.  
     - Comparison results.  

---

## 🛠️ **How It Works**

### **Workflow**
1. **Select Files**: Choose a single file or a folder.  
2. **Generate Hash**: Compute the MD5 hash of selected files.  
3. **Compare Hash**: Verify the generated hash against a reference.  
4. **Log Metadata**: Save details to a CSV or SQLite database.  
5. **Generate Report**: Export findings for documentation.  

---

## 🎨 **Screenshots**

### **Front Panel UI**  
_(Insert a screenshot of the intuitive user interface here!)_

### **Block Diagram Overview**  
_(Insert a screenshot of your organized block diagram here!)_

---

## 💻 **Getting Started**

### **Prerequisites**
- **LabVIEW 2020** (or later).  
- **benchmarks_fileMD5.vi** file integrated into the project.  
- Optional: LabVIEW **Report Generation Toolkit** for advanced report features.  

### **Installation**
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/digital-forensics-toolkit.git
   ```
2. Open the **DigitalForensicsToolkit.vi** file in LabVIEW.

---

## 📖 **Usage Guide**

1. **Run the VI**: Open the toolkit in LabVIEW and press the **Run** button.  
2. **Select File(s)**: Use the **File Dialog** to choose files or directories.  
3. **Generate Hash**: Click **"Generate MD5"** to compute hashes.  
4. **Verify Hash**: Input a reference hash and click **"Verify"** to compare.  
5. **Log Metadata**: Click **"Save Evidence"** to log results.  
6. **Generate Report**: Export detailed forensic reports for documentation.

---

## 🔍 **Use Cases**

- **File Integrity Verification**: Ensure files haven't been tampered with.  
- **Evidence Documentation**: Log file metadata and hash values for investigations.  
- **Batch Analysis**: Quickly analyze and hash multiple files in a directory.  

---

## 🤝 **Contributing**

We welcome contributions! Here's how you can help:  
1. Fork the repository.  
2. Create a branch for your feature or bug fix.  
3. Submit a pull request for review.  

---


## ❤️ **Acknowledgments**

Special thanks to:  
- **The LabVIEW Community** for their continuous support.  
- **Forensic Analysts** who inspire innovation in digital investigation tools.

---

## ⭐ **Star This Repo**

If this project is helpful, please **star this repository** on GitHub! It encourages further development and helps others discover it.  

---

### **Dynamic, feature-rich, and user-friendly—this toolkit is your entry point into the world of digital forensics. Dive in and start exploring!**
