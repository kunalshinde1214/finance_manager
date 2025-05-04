# Finance_Manager
# Personal Finance Manager

## Overview
The Personal Finance Manager is a web-based application designed to help individuals and families track their income, expenses, and savings. With a sleek, finance-focused design, it provides an intuitive interface to input financial data, visualize expense breakdowns, and receive tailored financial tips. The application features a modern aesthetic with light purple and dark tones, incorporating financial elements like currency symbols and charts to enhance the user experience.

## Features
- **User Orientation**: Choose to manage finances for an individual or a family.
- **Income and Expense Tracking**: Input monthly income and detailed expense categories (e.g., rent, utilities, groceries, vehicle costs, dining, entertainment).
- **Simulated UPI Data**: Toggle to populate expense fields with sample data for quick testing.
- **Financial Summary**: View total income, expenses, savings, and average daily expenditure.
- **Visualizations**:
  - Pie chart for expense breakdown (housing, utilities, food, other).
  - Bar chart for cash flow (income, expenses, savings).
- **Financial Tips**: Receive dynamic tips based on your savings rate.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Custom Styling**: Light purple and dark color scheme with gold accents, subtle currency symbol patterns, and particle animations for a modern financial look.

## Technologies Used
- **HTML5**: Structure of the web application.
- **CSS3**: Styling with custom variables, gradients, and animations.
- **JavaScript**: Logic for form handling, calculations, and dynamic UI updates.
- **Particles.js**: Background particle animations for visual appeal.
- **Font Awesome**: Icons for enhanced UI elements.

## Setup Instructions
1. **Clone or Download**:
   - Clone the repository or download the project files.
2. **Project Structure**:
   - Ensure the `index.html` file is in the root directory.
   - No additional files are required, as external libraries are loaded via CDN.
3. **Serve the Application**:
   - Option 1: Open `index.html` directly in a modern web browser (e.g., Chrome, Firefox).
   - Option 2: Use a local server for better performance:
     ```bash
     npx http-server
     ```
     Then navigate to `http://localhost:8080` in your browser.
4. **Dependencies**:
   - No local dependencies are required. The application uses the following CDNs:
     - Font Awesome: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`
     - Particles.js: `https://cdnjs.cloudflare.com/ajax/libs/particles.js/2.0.0/particles.min.js`

## Usage
1. **Access the Tool**:
   - Open the application in a browser.
   - Click "Get Started" or "Start Planning" to scroll to the financial planning tool.
2. **Step-by-Step Process**:
   - **Step 1: Orientation** - Select whether you're managing finances for yourself or your family.
   - **Step 2: Income** - Enter your monthly income (after tax) and select the primary income source.
   - **Step 3: Expenses** - Input expense details (rent, utilities, etc.). Optionally toggle "Use simulated UPI data" to auto-fill sample values.
   - **Step 4: Results** - Click "Calculate" to view your financial summary, including charts and personalized tips.
3. **Reset**:
   - Click "Start Over" in the results step to clear all inputs and return to the orientation step.

## Design Notes
- **Color Scheme**: Light purple (`#b19cd9`) for a modern financial aesthetic, dark purple-blue (`#2f2f5b`) for depth, and gold (`#d4a017`) for wealth accents.
- **Financial Elements**: A subtle currency symbol (`$`) pattern in the background reinforces the financial theme.
- **Interactivity**: Particle animations and smooth transitions enhance the user experience while maintaining a professional look.
- **Accessibility**: High-contrast text and clear form labels ensure usability.

## Future Enhancements
- Add support for saving financial data locally using LocalStorage.
- Implement additional visualizations, such as trend charts for monthly savings.
- Integrate a currency converter for multi-currency support.
- Enhance accessibility with ARIA labels and keyboard navigation.

## License
© 2025 FinanceManager. All rights reserved.

## Contact
For questions or feedback, please reach out via the "Contact" link in the application.
