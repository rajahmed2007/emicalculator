# EMI Calculator 

A sleek, modern, and user-friendly Equated Monthly Installment (EMI) calculator built with **HTML**, **Tailwind CSS**, and **JavaScript**. This tool allows users to easily calculate their loan EMIs, understand the total interest payable, and view a detailed amortization schedule.

![EMI Calculator Screenshot](https://i.ibb.co/8gvBnfyF/image.png)


## 🚀 Features

* **Calculate Monthly EMI:** Quickly determine your monthly loan payment.
* **Total Interest & Payment:** Understand the full cost of your loan.
* **Down Payment Option:** Factor in your initial down payment for more accurate calculations.
* **Loan Start Date:** Select a start date to generate a dated payment schedule.
* **Detailed Amortization Schedule:** View a month-by-month breakdown of principal and interest payments, along with the outstanding balance.
* **Responsive Design:** Looks great and functions well on desktops, tablets, and mobile devices.
* **Modern UI:** Clean, intuitive interface styled with Tailwind CSS.
* **Input Validation:** Provides feedback for incorrect or missing inputs.
* **Loading Indicator:** A smooth loading spinner during calculations.

## 🛠️ Technologies Used

* **HTML5:** For the basic structure and content.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development (used via CDN).
* **JavaScript (Vanilla):** For all calculations, interactivity, and DOM manipulation.
* **Google Fonts (Inter):** For clean and readable typography.

## 💡 How it Works

The calculator uses the standard EMI formula:

$$
EMI = P \times r \times \frac{(1 + r)^n}{(1 + r)^n - 1}
$$
Where:
* **P** = Principal Loan Amount (Loan Amount - Down Payment)
* **r** = Monthly Interest Rate (Annual Rate / 12 / 100)
* **n** = Loan Tenure in Months (Tenure in Years * 12)

It then iteratively calculates the interest and principal paid for each month to generate the amortization schedule.

## ⚙️ Getting Started

This project is a single HTML file and uses CDN links for Tailwind CSS, so there are no complex setup steps.

1.  **Clone the repository (optional):**
    ```bash
    git clone https://github.com/rajahmed2007/emicalculator
    cd emicalculator
    ```
    *OR*
2.  **Download:**
    * Simply download the `index.html` file.
3.  **Run:**
    * Open the `index.html` file in your favorite web browser (like Chrome, Firefox, Edge, or Safari).

That's it! You can now use the EMI calculator.

## 📖 Usage

1.  **Open** the `index.html` file in your browser.
2.  **Fill in the Loan Details:**
    * **Loan Amount (₹):** Enter the total amount you wish to borrow.
    * **Annual Interest Rate (%):** Enter the yearly interest rate.
    * **Loan Tenure (Years):** Enter the duration of the loan in years.
    * **Down Payment (₹):** (Optional) Enter any down payment amount (defaults to 0).
    * **Loan Start Date:** Select the date when your loan begins.
3.  **Click** the "Calculate EMI" button.
4.  **View the Results:** The Monthly EMI, Total Interest Payable, and Total Payment will be displayed.
5.  **Check the Schedule:** A detailed EMI Payment Schedule will appear below the results, showing the breakdown for each month.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find any bugs, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

## 📄 License

This project is open-source. You can consider adding a license like the [MIT License](https://opensource.org/licenses/MIT).

## 👨‍💻 Author

* **Raj Ahmed**
* GitHub: [rajahmed2007](http://github.com/rajahmed2007)

---

