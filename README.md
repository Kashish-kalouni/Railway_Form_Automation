# 📋 Railway Ticket Registration and Cancellation Automation

### 🔹 About the Project:
This project is a **Python-based automation** tool that allows users to **register** for a railway journey or **cancel** their booked tickets easily.  
The system also **generates PDF forms** and **saves the data into CSV files** automatically for record keeping.

It is designed to handle **multiple passengers** at once and ensures **neatly formatted outputs**.

---

# 🚂 Features:

- ✍️ **Ticket Registration**:
  - Capture passenger details like name, age, gender, train details, payment info, etc.
  - Auto-generate a **Registration Form** in PDF format.
  - Save all registration data into a **CSV file** (`registration_details.csv`).

- ❌ **Ticket Cancellation**:
  - Capture cancellation details like passenger names, PNR number, journey date, ticket amount, reason, and refund mode.
  - Handle **multiple passengers** cancellation at once.
  - Auto-generate a **Cancellation Form** in PDF format.
  - Save all cancellation data into a **CSV file** (`cancellation_details.csv`).

- 📄 **PDF Generation**:
  - Nicely formatted Railway Registration/Cancellation forms generated dynamically.
  - Clean fonts, professional layout without any unwanted tags.

- 💾 **Data Storage**:
  - All details saved safely into CSV files for future references.

- 🧹 **Neat and Clean Output**:
  - Names and details are properly formatted.
  - No raw list outputs, everything displayed user-friendly.

---

# ⚙️ Technologies Used:

- **Python 3.x**
- **FPDF Library** (for PDF generation)
- **CSV Module** (for data storage)

---

# 📦 Project Structure:

```plaintext
|-- Railway_registration_form.ipynb
|-- registration_details.csv
|-- cancellation_details.csv
|-- registration_form.pdf
|-- cancellation_form.pdf


---

## 🏃‍♂️ How to Run
1. **Install required libraries**  
    ```bash
    pip install fpdf
    ```
2. **Run the script or notebook**  
    ```bash
    python Railway_registration_form.py
    # —or—
    jupyter notebook Railway_registration_form.ipynb
    ```
3. **Choose mode**  
   - Type `Registration` or `Cancellation` when prompted  
4. **Fill in the requested details**  
5. **Get your**  
   - **PDF form**  
   - **Saved CSV record**  
6. **Done!** 🚀

---

## 💡 Future Enhancements
- **Add GUI interface** (Tkinter / PyQT)  
- **Enable online email sending** of registration/cancellation PDFs  
- **Integrate with a database** (SQL / NoSQL) for scalable storage  

---

## 🙌 Contribution:
Project is open for learning and improvements.
Feel free to suggest or raise issues! 🚀
---
## ✍️ Author:
Made with ❤️ by Kashish Kalouni.

---
## 🔥 Small Tagline:
"No more long queues at railway counters — Book and Cancel your tickets with one click!"
