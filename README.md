# Selenium-Login-Page-Automation

🟢 OrangeHRM Login Automation ✅

📌 Project Description

This project automates the Login functionality of the OrangeHRM Demo Site using Selenium WebDriver with Java in Eclipse IDE.
It verifies whether a user with valid credentials (Admin / admin123) can successfully log in to the system.

💡 Purpose:

The project demonstrates real-time automation testing of login functionality in a web application. It helps testers and developers ensure that user authentication works correctly and that invalid credentials are handled properly.

🏢 About OrangeHRM Demo

OrangeHRM is an open-source Human Resource Management (HRM) system used for managing HR processes like employee information, leave management, and payroll.

Demo Site: https://opensource-demo.orangehrmlive.com

Credentials for testing:

Username: Admin

Password: admin123

This project uses the demo site to practice login page automation without affecting real systems.

🛠️ Tools & Technologies Used

Programming Language: Java

Automation Tool: Selenium WebDriver

IDE: Eclipse

Browser: Google Chrome (via ChromeDriver)

Test Management: Excel (for documenting test cases)

📂 Project Structure

Selenium-Login-Page-Automation/
├── src/
│   └── loginpage.java         # Selenium automation script
├── TestCases/
│   └── Login_TestCases.xlsx   # Manual test cases in Excel
├── README.md                  # Project documentation

🧪 Testing Techniques Used

Manual Testing:

Writing Excel test cases to validate login scenarios.

Covers positive & negative testing (valid credentials, invalid password, empty fields).

Automation Testing:

Selenium WebDriver automates browser actions (input username/password, click login).

Validation: Checks whether the login redirects to the dashboard successfully.

Testing Types Covered:

Functional Testing ✅

Positive & Negative Testing ✅

UI Validation ✅

⚙️ How This Project Works

Launch Chrome browser using Selenium.

Open the OrangeHRM Demo site.

Enter the username and password.

Click the Login button.

Verify whether login is successful by checking the dashboard page URL.

Log the result in the console:

✅ Login Successful → Test Passed

❌ Login Failed → Test Failed

Close the browser.

🎯 Domain

Domain: Human Resource Management (HRM)

Purpose: Demonstrates login page validation in HRM software using automation.

🛠️ Implementation Benefits

Reduces manual effort in repetitive login testing.

Ensures accuracy and consistency in test results.

Can be extended to full regression testing of HRM modules.

Ideal for learning Selenium, Java, and test automation in real-time applications.

📊 Sample Test Cases (Excel)
Test Case ID	Test Scenario	Input Username	Input Password	Expected Result
TC001	Valid Login	Admin	admin123	Login Successful
TC002	Invalid Password	Admin	wrongpass	Error Message
TC003	Empty Username	(blank)	admin123	Error Message
TC004	Empty Password	Admin	(blank)	Error Message
TC005	Both fields empty	(blank)	(blank)	Error Message
🚀 How to Run the Project

Clone the repository

git clone https://github.com/<your-username>/Selenium-Login-Page-Automation.git
cd Selenium-Login-Page-Automation


Set up Selenium in Eclipse IDE

Add Selenium Java Client to project build path.

Download ChromeDriver and set its path in the script (if not using WebDriverManager).

Run the Automation Script

Run loginpage.java as a Java application in Eclipse.

Check the console for test results.

🔮 Future Enhancements

Integrate with TestNG / JUnit for structured testing.

Generate HTML test reports using ExtentReports.

Include data-driven testing from Excel/CSV files.

Automate additional HRM modules (Employee Management, Leave, Payroll).

📸 Screenshots (Optional)

Screenshot of login page automation in action

Dashboard page after successful login
