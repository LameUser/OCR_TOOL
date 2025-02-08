# OCR_TOOL <img src="https://github.com/user-attachments/assets/bd2c94d1-ea62-4837-bf08-be0e873c8b8f" alt="OCRTOOL" width="60" height="60">



## Convert PDF to Excel Locally

## 📜 Description
This is a **Python GUI application** that extracts tables from **PDF files** and converts them into **Excel spreadsheets** using **Camelot** and **Tkinter**.

🚀 **Features:**
- Extracts tables from PDFs using **Camelot**.
- Saves extracted data as an **Excel file**.
- Automatically detects headers in tables.
- Provides a **GUI for selecting files** (built with Tkinter).
- Runs **completely offline**.

---

## 🛠️ **Requirements**
This application requires **Python 3.10 or 3.11** (Python 3.13 is not supported due to Camelot dependency issues).

### **📦 Install Dependencies**
1. Clone the repository:
   ```sh
   git clone https://github.com/LameUser/OCR_TOOL.git
   cd OCR_TOOL
   ```
2. Create a Virtual Environment (Optional but Recommended):
   `python -m venv .venv`

3. Activate the Virtual Environment:
   - Windows (PowerShell):
      `.venv\Scripts\Activate`
   - Mac/Linux:
     `source .venv/bin/activate`

4. Install Dependencies:
   `pip install camelot-py[cv] pandas openpyxl tkinter`

## 🔥 **How to Use**

1. Run the script:
   `python ocrtool.py`

2. Select a PDF file that contains tables.

3. Choose where to save the Excel file.

4. Click "Convert to Excel" and wait for success confirmation.

5. Open the generated Excel file 📊

## 🤝 **Contributing**
**Feel free to fork the repository and submit a pull request!** 🚀

## 📝 **License**
This project is licensed under the MIT License.
      
