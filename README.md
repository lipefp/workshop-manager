# 🚗 Workshop Management System

A desktop application for managing mechanical and auto-electrical workshops — focused on fast service, financial organization, and document issuance. Built with Python and a clean PyQt5 interface.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Qt](https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

---

## 📸 Preview

| Main Menu | Service Orders | Financial Report |
| --- | --- | --- |
| ![Main menu](assets/menu_principal.png) | ![Service orders](assets/menu_gerar_notas.png) | ![Report](assets/menu_relatorio.png) |

---

## 🚀 Features

- **📋 Customer & Vehicle Registration** — with automatic license-plate validation (Mercosur and old standards).
- **📝 Service Order Generation** — quick creation of orders with multiple items (parts and labor).
- **🖨️ Professional PDF Export** — quotes and receipts in PDF with a corporate layout, ready to print or send via WhatsApp.
- **💰 Financial Control** — instant report of accumulated revenue and cash flow.
- **📂 Service History** — full record of everything done on a given vehicle.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **GUI:** PyQt5
- **Database:** SQLite3 (native — no external server needed)
- **PDF Engine:** ReportLab

---

## 🗂️ Project Structure

```
app-notas-fiscais/
├── src/
│   ├── main.py          # Main interface and logic
│   └── models/
│       └── db.py        # Database layer (SQLite)
├── assets/              # Screenshots
├── requirements.txt
└── README.md
```

---

## ▶️ Getting Started

```bash
# clone
git clone https://github.com/lipefp/app-notas-fiscais.git
cd app-notas-fiscais

# virtual environment
python -m venv .venv
source .venv/bin/activate        # Linux/macOS
# .venv\Scripts\activate         # Windows

# dependencies
pip install -r requirements.txt

# run (from the src folder)
cd src
python main.py
```

---

## 👤 Author

**Felipe Diniz** · [GitHub](https://github.com/lipefp) · [LinkedIn](https://www.linkedin.com/in/felipe-diniz-39237b288)
