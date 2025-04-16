**##SKILLS GAINED##**

* Test Automation Framework Design  
* Selenium WebDriver Integration  
* TestNG Suite Management  
* Maven Dependency Management  
* HTML Report Generation  
* Page Object Model (POM) Implementation  
* Modular Code Organization  
* Configuration Management  
* Custom Wait Implementation  
* JSON Data Handling  
* Utility Class Development  
* Listener Integration in TestNG  
* Extent Reports Customization  
* Cross-Browser Testing Setup  
* Reusable Code Development  
* Debugging and Troubleshooting Test Cases  
* Scalability and Maintenance of Frameworks  

**Project Structure Breakdown**  
Root Directory: SeleniumAutomation_1/  

**pom.xml**  
The Maven Project Object Model (POM) file. Manages dependencies, build lifecycle, and plugins for the project.  

**Framework Structure**  
  _**src/main/java**_  
  **meenakshi.POM_Page**  
   Implements the Page Object Model (POM) design.  
   Subfolders organize pages by category:  
     * CheckoutPage  
     *  Landing Page  
     * Products Page  
     * Summary Page  
     
**utils**  
 Resuable Functionalities  
 Contains utility methods for custom explicit/implicit waits.  

_**src/test/java**_  
 **Automation_Project1**  
  * Base/  
     A base class for test setup and teardown  
  * Testcase1/  
  * Testcase2/  
    Test classes for each page  

**_Global_**  
   * Extent Reports/  
   Contains HTML test execution reports, generated for each test run.  
   
   * MyListeners/  
   Implements TestNG listeners for logging and reporting.  
   
   * data.json/  
   Contains login credentials or other test data.  
   
   * GlobalData.properties/  
   Reads and fetches values from config.properties  
   
    
   **KeyHighlights**  
* _**TestNG and Maven**:_ A well-organized framework leveraging TestNG for test execution and Maven for dependency management.  
* _**Page Object Model (POM)**:_ Follows POM design for better maintainability and readability.  
* _**Modular Design**:_ Separate modules for pages, utilities, and tests enhance scalability.  
* _**Reporting**:_ Includes timestamped HTML reports for test execution tracking.  
* _**Reusable Components**:_ Shared code in base and utils promotes reusability and reduces redundancy.  
* _**Industry Standard**:_ This framework structure aligns with industry standards for Selenium-based test automation.  


![image](https://github.com/user-attachments/assets/01a02fe6-bde1-4505-8283-7a8aa1dc83a5)

     
