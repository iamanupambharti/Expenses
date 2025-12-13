# Expense Tracker

A modern, feature-rich expense tracker web application that helps you manage your finances with ease. This application is built with React and Tailwind CSS, and it leverages the power of AI to make expense logging faster and more intuitive.

## Features

- **Manual Entry:** Add expenses manually with detailed information.
- **Expense Management:**
  - View all your expenses in a clean, organized table.
  - Sort expenses by date.
  - Search for specific expenses by name, location, or date.
  - Delete expenses you no longer need.
  - Undo your last action to prevent mistakes.
- **Data Import and Export:**
  - Import your existing expense data from an Excel file.
  - Export your expenses to a beautifully formatted Excel sheet, complete with a total summary.
- **AI-Powered Insights:**
  - Get a detailed analysis of your spending habits with the click of a button.
  - The AI provides a summary, categorizes your expenses, and offers a money-saving tip.
  - **Note:** This feature requires a Gemini API key.
- **Customization:**
  - Manage a list of your common expense locations.
  - Set your preferred currency symbol.
- **Widget Mode:** Switch to a compact "widget" view for quick and easy expense entry without the full dashboard.
- **Local Storage:** Your data is saved securely in your browser's local storage, so you don't have to worry about losing it.
- **Note:** Make sure to not clean your browser data or cookies of this website, otherwise you may lose the data if you didn't exported the Excel Sheet . 
- **Responsive Design:** The application is fully responsive and works seamlessly on desktops, tablets, and mobile devices.

## Tech Stack

- **Frontend:** React, Tailwind CSS
- **AI:** Google Gemini
- **Libraries:**
  - `lucide-react` for icons
  - `xlsx-js-style` for Excel export
  - `marked` for rendering markdown

## How to Use

1. Open the [ExpenseTracker.](www.expensestrackers.vercel.app) in your web browser.
2. **Generate Google Gemini API Key:**
   - Go to the [Google AI Studio](https://aistudio.google.com/app/apikey) website.
   - Click on "Get API key in a new project" or "Create API key" if you have an existing project.
   - Copy the generated API key.
3. To use the AI-powered features, go to **Settings** in the Expense Tracker application and enter your Gemini API key.
4. Start adding your expenses!

## Screenshots

![Widget View](/widget.png)
![Manual Entry](/Manual.png)
![Settings](/Settings.png)
![AI-Insights](/AI-Insights.png)

**Note:** Currently working on Smart Add and voice transcription.Failed to implement. Come soon...
