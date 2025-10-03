Nopcommerce Test Automation Suite - README Structure
Automated test suite for an e-commerce website using Java, Selenium WebDriver, and TestNG following the Page Object Model (POM) design pattern.
📌 Badges
Java | Selenium | TestNG | Maven
🚀 How to Run
1. Clone the repository:
   git clone https://github.com/YOUR_USERNAME/Ecommerce_TestAutomation.git
2. Build the project with Maven:
   mvn clean install
3. Run the test suite:
   mvn test
📂 Project Structure
Nopcommerce_TestAutomation/
│
├── src/
│   ├── main/java       # Page Objects & utilities
│   └── test/java       # Test classes
│   └── test/resources  # Test data / configs
│
├── screenshots/        # Failure screenshots (excluded from Git)
├── pom.xml             # Maven dependencies
├── testng.xml          # TestNG suite configuration
└── README.md           # Project documentation

✅ Features Covered
- User Registration  
  - Negative cases (invalid inputs, missing fields, mismatches)  
  - Happy path registration  

- Login Tests  

- Product Search  

- Product Comparison  

- Wishlist Functionality  

- Shopping Cart Functionality  

- Checkout Process  
  - Negative cases (invalid form fields, missing data)  
  - Happy path checkout
💡 Notes
- Uses Page Object Model (POM) for test structure  
- Includes screenshot capture on failure  
- Uses soft assertions for flexible validation  
- Designed for easy extension with new test cases
👩‍💻 Created with ❤️ for learning and practicing test automation.
