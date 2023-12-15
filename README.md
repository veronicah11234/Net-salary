# Net Salary Calculator

This is a simple web-based application to calculate an individual's Net Salary based on the provided basic salary and benefits. The calculator takes into account Payee (Tax), NHIF Deductions, NSSF Deductions, gross salary, and net salary.

## Usage

1. Open the `index.html` file in a web browser.
2. Fill in the required information:
   - Basic Salary: Enter the individual's basic salary.
   - Benefits: Enter any additional benefits.
3. Click the "Calculate Net Salary" button.
4. The calculated salary details will be displayed on the page.

## How It Works

The calculation is based on the following components:
- **Gross Salary:** Sum of Basic Salary and Benefits.
- **Payee (Tax):** Calculated based on the provided KRA tax values.
- **NHIF Deductions:** Calculated based on the provided NHIF values.
- **NSSF Deductions:** Calculated based on the provided NSSF values.
- **Net Salary:** Gross Salary minus Payee, NHIF, and NSSF deductions.

## Additional Notes

- This calculator uses dummy values for KRA, NHIF, and NSSF. Replace the placeholder values with the actual values.
- The actual calculation logic is in the JavaScript section of the HTML file.

Feel free to customize the application to meet your specific requirements.

## License

This project is licensed under the [MIT License](LICENSE).
