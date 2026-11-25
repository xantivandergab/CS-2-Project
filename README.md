# CartCheck: A Pre-Checkout Budget and Price Tracker 

## Project Description
A Python console system that acts as an advanced pre-checkout budget companion. It allows users to track quantities, select from preset school supplies, monitor live budget limits, and automatically export a text-file receipt before paying.

## Features

Preset Item Menu: A built-in catalog of 5 common school supplies using Python dictionary lookup, allowing users to select items quickly using number codes. 

Custom Item Entry with Validation: An option to manually type in unlisted items and prices, backed by input validation guardrails to block negative numbers, letters, or invalid inputs from crashing the program. 

Quantity Multiplier: Allows users to input the number of pieces they want for any selected item, automatically multiplying the cost to calculate the subtotal. Planned Outputs: Interactive 

Menu Display: A clean, numbered list of available preset and custom options shown on the console.

Live Budget Updates: Real-time feedback showing the updated running total and remaining budget after each entry. 

Budget Warning Alerts: Instant notifications if an added item exceeds the user's set spending limit. 

Final Itemized Summary: A receipt-style summary displayed on the console and automatically exported as a text file (receipt.txt), listing all items, quantities, subtotals, and the final total cost. 

Live Budget Tracker & Warning System: Real-time budget monitoring that calculates running totals against an initial budget limit and alerts the user immediately if an item exceeds their remaining balance. 

Receipt Text File Export: Automatically generates and saves a downloadable receipt.txt file containing the complete itemized purchase summary at the end of the session. 

Modular Code Design: Built cleanly using Python functions (def) to organize the program into structured, professional logic blocks.

Remove Item: If the total price exceeds the budget, the user is allowed to remove an item from the list.

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

[4] Remove Item

[5] Checkout

Select option: 1

Enter quantity: 2

Added: 2x Notebook (₱70.00) | Remaining Budget: ₱80.00

[1] Notebook - ₱35.00

[2] Ballpen - ₱12.00

[3] Add Custom Item

[4] Remove Item

[5] Checkout

Select option: 3

Enter custom item name: Correction Tape

Enter custom item price: 45.00

Enter quantity: 1

Added: 1x Correction Tape (₱45.00) | Remaining Budget: ₱35.00

Select option: 5 (Checkout)

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
