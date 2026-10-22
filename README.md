# Pre-Checkout Price Tally & Budget Tracker

## Project Description
A Python console system that acts as an advanced pre-checkout budget companion. It allows users to track quantities, select from preset school supplies, monitor live budget limits, and automatically export a text-file receipt before paying.

## Features
-Preset Item Menu: Quick selection from a catalog of common school supplies using number codes.

-Quantity Multiplier: Choose how many pieces of an item you want, automatically multiplying the price.

-Custom Item Entry: Manual entry for unlisted items with strict input validation to block negative numbers or typos.

-Live Budget Tracker: Real-time budget monitoring with instant warnings if an added item exceeds your limit.

-Receipt Text File Export: Automatically generates and saves a downloadable receipt.txt file of your purchase summary.

-Modular Design: Built cleanly using Python functions (def) for structured, professional code organization.

## How to run the program
1. Open a Python IDE (such as VS Code or Programiz).
2. Copy and paste the source code into a new file.
3. Run the script.
4. Follow the console instructions to set your budget, choose or input items, and view your summary.

## Inputs Needed
-Initial budget limit
-Menu selections or custom item names and prices
-Item quantities (number of pieces)
-Checkout/Exit command

## Example Output
Enter your budget limit: 150.00

[1] Notebook - ₱35.00

[2] Ballpen - ₱12.00

[3] Add Custom Item

Select option: 1

Enter quantity: 2

Added: 2x Notebook (₱70.00) | Remaining Budget: ₱80.00

[1] Notebook - ₱35.00

[2] Ballpen - ₱12.00

[3] Add Custom Item

Select option: 3

Enter custom item name: Correction Tape

Enter custom item price: 45.00

Enter quantity: 1

Added: 1x Correction Tape (₱45.00) | Remaining Budget: ₱35.00

Select option: 0 (Checkout)

Summary of Items:
2x Notebook - P70.00
1x Correction Tape - P45.00
TOTAL PRICE: P115.00

[Success] Receipt successfully exported to 'receipt.txt'!


## Author
- Student 1: Vander Gil S. Concepcion (entered the project description, the initial step-by-step process on how to run the program, inputs needed, and example output)
- Student 2: Xanti Manuel C. Matira (did the changelog, fixed the readme file)
- Student 3: Gabriel Nico B. Udtohan (entered the features, checked for mistakes, and did finalization of the whole)
  
  JASMINE
