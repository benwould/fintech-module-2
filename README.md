# Loan Qualification Application

An application for checking whether or not a customer qualifies for a loan or loans.
Given a set of lenders who are willing to offer a loan, gather necessary information
from the customer and deduce if they qualify. The primary qualifications include:
- Monthly Debt Ratio
- Loan to Value Ratio

---

## Technologies

This is a python application using the library `questionary` to query the user for 
necessary information.  We also use `fire` to make this a CLI for the customer.

---

## Installation Guide

This application will be run from source code.  Source code files will be executed from 
the command line via Windows `cmd` window or git bash.  The main executable is `app.py`.

---

## Usage

The main executable is `app.py` and will be executed from command line as follows:
`>python app.py`

The user is then prompted for the following information:
- Credit Score
- Monthly Debt
- Monthly Income
- Desired Loan Amount
- Home Value

These inputs are used to calculate loan qualification ratios and are compared to a `daily_rate_sheet'`
provided by lenders.  Contents of the rate sheet include:
- Lender
- Max Loan Amount
- Max LTV
- Max DTI
- Min Credit Score
- Interest Rate


---

## Contributors

This application was written by Ben Wood in conjunction with folks at [UW Fintech](https://uwa.bootcampcontent.com/UWA-Bootcamp/UW-VIRT-FIN-PT-10-2022-U-B).

---

## License

This application is licensed under the GNU General Public License. See here for details.

[GNU Public License](https://github.com/IQAndreas/markdown-licenses/blob/master/gnu-gpl-v3.0.md)