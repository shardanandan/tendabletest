Tendable Cypress Automation Test
This project contains Cypress automation scripts for testing various functionalities on the Tendable website.
How to Run the Tests
1.	Clone this repository to your local machine.
2.	Ensure you have Node.js and npm installed on your machine.
3.	Install Cypress by running npm install cypress in your terminal.
4.	Navigate to the project directory in your terminal.
5.	Run the command npx cypress open to open the Cypress Test Runner.
6.	Click on the desired test file in the Cypress Test Runner to run the test.
Strategy Employed
1. Accessibility Testing of Top-Level Menus
•	Description: The script verifies the accessibility of the top-level menus: Home, Our Story, Our Solution, and Why Tendable.
•	Approach: Uses Cypress commands to confirm the presence and functionality of each menu item.
2. Verification of "Request a Demo" Button
•	Description: The script checks for the presence and activity of the "Request a Demo" button on each of the top-level menu pages.
•	Approach: Navigates to each menu page and verifies the presence and functionality of the button.
3. Contact Us Form Submission Test
•	Description: The script navigates to the "Contact Us" section, selects "Marketing" from the contact type dropdown, and completes the form excluding the "Message" field. It then verifies that an error message arises upon submission.
•	Approach: Utilizes Cypress commands to interact with the form, submit it, and confirm the appearance of the error message.
This strategy ensures comprehensive testing of key functionalities on the Tendable website, covering accessibility, button functionality, and form submission.

