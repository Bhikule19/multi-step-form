# Multi-Step Form

## Overview

This project is a multi-step form built with HTML, CSS, and JavaScript. It allows users to navigate through multiple steps to select a plan, add addons, and review their selection before submitting. The form includes various validation checks to ensure accurate user input.

![Multi stop form](./design/desktop-preview.jpg)

## Key Features

- Multi-step navigation
- Form validation (email format, phone number format, and required fields)
- Dynamic price update based on plan type (monthly or yearly)
- Addon selection with dynamic price update
- User-friendly interface

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To run this project on your local system, follow these steps:

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Bhikule19/multi-step-form.git
   ```
2. Navigate to the project directory:
   ```bash
   cd multi-step-form
   ```
3. Open `index.html` in your web browser:
   ```bash
   open index.html
   ```
   Alternatively, you can open the file directly in your web browser by dragging and dropping it into the browser window.

## Form Validation

- **Email Format Validation:** Ensures that the email input follows the standard email format.
- **Phone Number Format Validation:** Ensures that the phone number input follows a specified format.
- **Step 3 Checkbox Validation:** Ensures that at least one addon is selected before proceeding to the next step.

## Dynamic Plan and Addon Price Update

- Prices for plans and addons update dynamically based on the user's selection of monthly or yearly plans.

## Navigation

- Users can navigate through the steps using "Next" and "Back" buttons.
- The "Change" link in the plan summary allows users to go back to the add-ons step to make adjustments.

## Deployed Link

The project is deployed and can be accessed at: [Deployed Link](https://multi-step-form-ten-taupe.vercel.app/)
