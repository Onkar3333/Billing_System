# 🧾 Java Billing System

A **Billing System** developed in **Java Swing** that allows businesses to generate and manage customer bills efficiently. The system includes support for:

- Product/service selection
- Quantity & price calculation
- GST/taxes
- Date and calendar integration
- Auto-calculation of total amount
- **Automatic PDF generation** of bills and local storage

---

## 📌 Features

- 🎛️ **Graphical User Interface (GUI)** using Java Swing.
- 📅 **Calendar and Date Picker** for invoice date selection.
- 🛍️ **Dynamic Item Entry** with quantity, price, and line total.
- 💰 **Automatic Tax Calculation** (e.g., GST/CGST/SGST).
- 🧾 **Real-Time Bill Preview**.
- 📤 **Export to PDF** (bills stored locally with customer name/date).
- 🔍 **Search Past Bills** (based on name/date).
- 🗃️ **Save bill data locally** in a structured directory.

---

## 🛠️ Tech Stack

| Technology       | Purpose                        |
|------------------|--------------------------------|
| Java             | Core programming language      |
| Java Swing       | GUI Development                |
| iText / OpenPDF  | PDF Generation Library         |
| Java Calendar    | Date Picker integration        |
| File I/O         | Store bills locally            |


---

## 🖥️ How It Works

1. Launch the application.
2. Enter customer details and select the billing date.
3. Add items/services dynamically (name, quantity, price).
4. Taxes are auto-applied (customizable).
5. Click **Generate Bill** to:
   - Calculate total
   - Show a preview
   - Generate a PDF
   - Save it locally in the `bills/` folder

---

## 🔧 How to Run

### Prerequisites:
- Java JDK 8 or later
- Any IDE (Eclipse, IntelliJ IDEA, NetBeans)
- iText JAR (or OpenPDF) for PDF export

### Steps:

1. Clone the repository or download the source files.
2. Import the project into your IDE.


```bash
javac -cp ".;lib/itext-2.1.7.jar" src/*.java
java -cp ".;lib/itext-2.1.7.jar;src" Main


