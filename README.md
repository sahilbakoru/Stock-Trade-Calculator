![Screenshot 2025-05-16 at 10 16 34 PM](https://github.com/user-attachments/assets/414def38-760a-4509-9a20-3170c9926a6d)

## Stock Trade Calculator

A sleek, web-based calculator for traders to plan stock purchases with precision. Compute key metrics like buying power, number of stocks, total cost, stop loss levels, and potential losses based on capital, stock price, leverage, and risk parameters. Built with a professional, dark-themed interface, it offers a clean, intuitive experience inspired by trading platforms.
### Features
Core Calculations: Determine stocks to buy, stop loss (long/short), and loss at stop, with red warnings () for high-risk losses exceeding a customizable threshold.

Two-Panel UI: Rounded, dark-themed input and result boxes, side-by-side on desktop, stacked on mobile for responsive usability.

Currency Support: Choose USD, EUR, or GBP with dynamic symbol updates.

Presets: Save, load, and delete trade setups for quick reuse via a dropdown interface.

Export Options: Download results as CSV or PDF for record-keeping.

Professional Design: Dark theme default with light mode toggle, varied button colors (blue, green, red, gray), minimal animations, and accessibility (ARIA, keyboard navigation).

Reliable: Real-time input validation, error handling, and local storage for presets and theme preferences.

### Tech Stack
Frontend: HTML, CSS (Roboto font, Flexbox), JavaScript

Dependency: jsPDF (via CDN) for PDF exports

No backend required: Runs locally in the browser

### Installation
**Clone the repository**: git clone https://github.com/sahilbakoru/Stock-Trade-Calculator.git

**Navigate to the project directory**: cd Stock-Trade-Calculator

**Open index.html in a modern browser (e.g., Chrome, Firefox) directly or via a local server.**


### Note 
 No additional setup or dependencies needed beyond a browser, as jsPDF is loaded via CDN.
 
### Usage
Enter Inputs:
Select currency (USD, EUR, GBP ..etc).

Input capital, stock price, stop loss (%), risk threshold (%), and leverage (1X–5X).

Real-time validation ensures accurate inputs.

Calculate:
Click the blue "Calculate" button or press Enter to view results.

Results include stocks to buy, total cost, stop loss levels, and losses, with high-risk losses (> threshold) in red.

Manage Presets:
Save setups with the green "Save" button.

Load or delete (red button) presets via the dropdown.

Export Results:
Use gray "Export as CSV" or "Export as PDF" buttons to download results.

Toggle Theme:
Click the theme button (/) to switch between dark and light modes.

