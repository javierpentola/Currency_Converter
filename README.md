### Project Documentation

---

#### **Project Overview**

**Project Name:** Currency Converter

**Technologies Used:**
- **HTML:** Provides the structure and layout of the web page.
- **CSS:** Utilizes TuiCss for styling, giving the application a retro MS-DOS-like appearance.
- **JavaScript:** Implements client-side logic to handle currency conversion and API requests.
- **ExchangeRate-API:** Supplies exchange rate data without the need for API keys.

**Description:** This project creates a web-based currency converter. It uses HTML for structure, CSS (with TuiCss) for styling, JavaScript for client-side functionality, and the ExchangeRate-API to retrieve current exchange rates. The application allows users to convert monetary amounts between selected currencies from a list of 20 options.

---

### **Technologies Usage**

1. **HTML:**
   - **Usage:** Defines the structure and content of the web application.
   - **Files:** Inline within the single HTML file.

2. **CSS:**
   - **Usage:** Styles the application to give it a retro MS-DOS appearance using TuiCss.
   - **Files:** Inline within the single HTML file, linked to TuiCss CDN.

3. **JavaScript:**
   - **Usage:** Handles user input, makes API requests, and updates the DOM with conversion results.
   - **Files:** Inline within the single HTML file.

4. **ExchangeRate-API:**
   - **Usage:** Provides exchange rate data for currency conversion.
   - **Files:** Accessed via JavaScript fetch requests.

---

### **Setup and Usage Instructions**

To set up and use the project after downloading the code, follow these steps:

1. **Clone the Repository:**
   - Use `git clone` to clone the repository to your local machine.
   ```bash
   git clone <repository_url>
   ```

2. **Navigate to the Project Directory:**
   - Change your working directory to the project folder.
   ```bash
   cd <project_directory>
   ```

3. **Install Dependencies:**
   - This project does not have external dependencies to install.

4. **Setup Specific Instructions:**
   - No additional setup is required for this project.

5. **Run the Application:**
   - Open the `index.html` file in a web browser.

6. **Access the Application:**
   - Open a web browser and navigate to the `index.html` file location. The application will be ready to use.

---

### **File Descriptions**

1. **`index.html`:**
   - Contains the complete structure, styling, and scripting for the currency converter application. It uses HTML for structure, inline CSS for styling with TuiCss, and JavaScript for functionality.

---

### **Project Functionality**

1. **Currency Selection:**
   - **Description:** Allows users to select the currencies to convert from and to using dropdown lists.
   - **Usage:** Select the desired currencies from the "From" and "To" dropdown lists.

2. **Amount Input:**
   - **Description:** Users can enter the amount they wish to convert in a text input field.
   - **Usage:** Enter the numeric value in the "Amount" text input field.

3. **Conversion Result:**
   - **Description:** Displays the converted amount after fetching and calculating the exchange rate.
   - **Usage:** Click the "Convert" button to perform the conversion and see the result in the "Result" section.
