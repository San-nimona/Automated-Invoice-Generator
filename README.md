# Automated-Invoice-Generator

Generate professional PDF invoices automatically from a CSV or Google Sheet.
This project is designed to help small businesses and freelancers save time by turning raw data into ready-to-send invoices.

# Features

Read client details from a CSV file (or Google Sheets with a small tweak).

Generate professional PDF invoices automatically.

Store invoices in an organized folder (/invoices).

Simple configuration, no manual design needed.

Easily extendable (add taxes, multiple items, or email delivery).

📂 Project Structure
invoice-generator/
│── data/
│   └── clients.csv
│── invoices/
│   └── (generated PDFs here)
│── main.py
│── README.md

# Example Input (clients.csv)
Client Name,Email,Service,Amount,Date
John Doe,john@example.com,Web Hosting,120,2025-09-01
Mary Smith,mary@example.com,Consulting,250,2025-09-03

# Example Output

Invoice_John_Doe_2025-09-01.pdf

Invoice_Mary_Smith_2025-09-03.pdf

Each invoice includes:

Your business details

Client details

Service provided

Date and amount

# How to Run

Clone the repository:

git clone https://github.com/San-nimona/Automated-invoice-generator.git

cd Automated-invoice-generator


Install dependencies:

pip install -r pandas
pip install -r reportlab



Add your client data into data/clients.csv.

Run the script:

python main.py


Check the invoices/ folder for generated PDFs.

# Future Recommendations

 Google Sheets integration (via gspread).

 Email invoices directly to clients.

 Support for multiple services/items per invoice.

 Add tax/VAT calculation.

 Web-based UI with FastAPI.

📜 License

This project is licensed under the MIT License – free to use and modify.
