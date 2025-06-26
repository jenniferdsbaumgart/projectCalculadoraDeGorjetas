
# Tip Calculator - Project

This project was built using HTML, CSS, and JavaScript during the Start Program by OneBitCode. The Tip Calculator allows users to calculate the tip amount based on the total bill, service quality, and the number of people splitting the bill.

## Project Overview

The application helps users calculate the tip amount when dining out or receiving services. It takes into account the total bill, the quality of the service, and the number of people splitting the bill. It calculates the total tip amount and how much each person should contribute.

## Features

- Input for Bill: Users can enter the total amount of the bill.
- Service Quality Selection: A dropdown allows users to select the quality of the service, which affects the tip percentage.
- People Count: Users can specify the number of people sharing the bill.
- Total Tip Calculation: The app calculates the total tip and how much each person should pay.
- Responsive Design: The app is designed to work well across different screen sizes.
## Tech Stack

**HTML**: For structuring the content.
**CSS**: For styling the calculator and ensuring a clean, user-friendly design.
**JavaScript**: For the logic that calculates the tip and handles user input.
## How to Use

1. Enter the total bill amount in the "Quanto ficou a conta?" field.
2. Select the service quality from the dropdown menu.
3. Enter the number of people who will be splitting the bill.
4. Click the "Calcular" button to calculate the total tip and how much each person should pay.
5. The tip amount will be displayed along with the per-person share.

## Code Explanation

**HTML Structure**

- The form asks for the bill amount, service quality, and the number of people.
- The result is displayed in a section called totalTip, showing the total tip and how much each person has to pay.

**JavaScript Logic**

- The calculateTip function calculates the tip based on the inputs.
- It uses the values from the form (bill, service quality, and number of people).
- If all required fields are filled, the function calculates the total tip and displays it.
- If there's more than one person splitting the bill, it shows how much each person should pay.
- If the input is incomplete or incorrect, the app will prompt the user to fill in all the fields.
## License

This project is for educational purposes and is open to use or modify as needed.
