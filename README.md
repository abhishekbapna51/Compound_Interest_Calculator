# Compound Interest Calculator

A simple and efficient compound interest calculator built using HTML, CSS, and JavaScript.  
The calculator supports two modes of time input: direct duration (years, months, days) or automatic calculation based on the loan start date.  
The tool also allows users to download a PDF report of the calculation.

Live Demo:  
https://abhishekbapna51.github.io/Compound_Interest_Calculator/

---

## Features

- Enter time duration manually (years, months, days)
- OR select loan start date to auto-calculate duration
- Monthly interest rate input
- Compound interest applied annually and monthly
- Real-time result display with structured output
- PDF download of the results (using jsPDF)
- Clean and responsive UI
- Bilingual labels (English + Hindi)

---

## Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6)  
- jsPDF for report generation  

---

## Folder Structure

```bash
.
└── index.html
```

---

## How It Works

### 1. Input Options
Users can choose between two modes:

**a. Duration Mode**  
- Years  
- Months  
- Days
  
**b. Date Mode**  
- Loan start date
The application auto-computes time duration up to today's date.

---

### 2. Interest Calculation Logic

- Monthly interest rate is applied.
- Annual compounding: 12 months = 1 year cycle.
- Remaining months and days are proportionally added.
- Formula applied iteratively to simulate compounding.

---

## Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/abhishekbapna51/Compound_Interest_Calculator.git
cd Compound_Interest_Calculator
```
### 2. Open the application
Simply open the file in any browser:
```bash
index.html
```

---

### PDF Report Generation
## The application uses jsPDF to create a downloadable report that includes:
- Principal amount
- Time duration
- Interest rate
- Interest amount
- Total payable amount
- The PDF is formatted for readability and includes a footer signature.

---
Author
Developed by Abhishek Bapna.
© 2025
