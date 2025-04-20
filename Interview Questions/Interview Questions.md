# **SQA Interview Questions with Answers**

### **1. What is Software Quality Assurance (SQA)?**
**Answer:**  
Software Quality Assurance (SQA) is a set of activities to ensure that the software meets the required quality standards and functions properly. It involves systematic monitoring of the software development processes and products, ensuring compliance with industry standards and best practices. SQA covers both the process (like planning, designing, and testing) and the product (delivering error-free software).

---

### **2. What is the difference between QA and SQA?**
**Answer:**  
- **QA (Quality Assurance)** focuses on preventing defects by improving the processes used in software development.
- **SQA (Software Quality Assurance)** includes QA but also specifically focuses on ensuring the software meets the required quality standards by verifying and validating it through different testing methodologies and techniques.

---

### **3. What are the different types of testing techniques?**
**Answer:**
1. **Static Testing:** Involves reviewing and analyzing the code without executing it. Examples include code reviews, walkthroughs, and inspections.
2. **Dynamic Testing:** Involves executing the code to verify the software's behavior, including functional and non-functional testing like performance testing.
3. **Black-box Testing:** Focuses on testing the functionality of the application without looking at the internal code structure.
4. **White-box Testing:** Involves testing the internal structure, design, and code of the application.
5. **Grey-box Testing:** A mix of both black-box and white-box testing, focusing on both the code and functionality.

---

### **4. What are the levels of testing?**
**Answer:**
1. **Unit Testing:** Testing individual units or components of the software to ensure they function correctly.
2. **Integration Testing:** Testing interactions between integrated components or systems to ensure they work together as expected.
3. **System Testing:** Testing the complete system as a whole to verify that the software meets the specified requirements.
4. **Acceptance Testing:** Testing to determine if the software is ready for delivery and meets the user requirements.
5. **Regression Testing:** Re-running tests to ensure that new changes have not introduced defects in previously working functionality.

---

### **5. What is the difference between severity and priority in testing?**
**Answer:**
- **Severity** refers to the impact a defect has on the system. It indicates how severe the defect is in terms of functionality.
  - **Example:** A bug that causes the system to crash is high severity.
- **Priority** refers to how soon the defect should be fixed based on the project's needs and urgency.
  - **Example:** A small UI bug on the homepage of a major marketing site may have high priority, even though it is of low severity.

---

### **6. What is the V-Model in software testing?**
**Answer:**  
The **V-Model** (Validation and Verification Model) is a software development model that emphasizes verification and validation of the software. Each development stage corresponds to a testing phase:
- **Requirements analysis → Unit Testing**
- **System Design → Integration Testing**
- **Detailed Design → System Testing**
- **Implementation → Acceptance Testing**

This model ensures that testing is done in parallel with development, which allows early defect detection.

---

### **7. What is the purpose of a test case?**
**Answer:**  
A **test case** is a set of conditions and variables used to determine whether a software application works correctly. The purpose is to ensure that the software behaves as expected under various conditions. Test cases contain:
- Test inputs
- Expected results
- Execution steps
- Test data

Test cases help in verifying the functionality and ensure that no defects are present.

---

### **8. What is regression testing?**
**Answer:**  
**Regression Testing** is the process of re-testing previously tested software after changes, such as new features or bug fixes, have been made. Its purpose is to ensure that the new changes have not introduced any defects into previously working functionality.

---

### **9. What is the difference between functional and non-functional testing?**
**Answer:**
- **Functional Testing:** Focuses on verifying the features and functionalities of the application, such as user login, database interaction, etc.
  - **Example:** Testing if a user can log in with correct credentials.
- **Non-Functional Testing:** Focuses on the non-functional aspects of the application, such as performance, usability, security, and scalability.
  - **Example:** Performance testing to check how the system handles a large number of users.

---

### **10. What is the difference between a bug, defect, and failure?**
**Answer:**
- **Bug:** A mistake in the software code that causes it to behave unexpectedly.
- **Defect:** A deviation from the expected behavior of the software, which can be caused by a bug.
- **Failure:** The inability of the system to perform its intended function due to defects.

---

### **11. What is the difference between verification and validation?**
**Answer:**
- **Verification** is the process of ensuring that the software is being built correctly according to specifications. It involves checking the code, design, and architecture.
  - **Example:** Code reviews, design inspections.
- **Validation** is the process of ensuring that the software meets the user's needs and requirements, ensuring that the product is built for the right purpose.
  - **Example:** User acceptance testing.

---

### **12. What is a test plan, and what does it contain?**
**Answer:**  
A **Test Plan** is a document that outlines the strategy and approach for testing the software. It helps ensure that the testing process is organized and systematic. A typical test plan contains:
- Test objectives
- Test scope
- Testing strategy
- Test deliverables
- Test resources
- Testing schedule
- Risks and mitigation plans

---

### **13. What is the difference between smoke testing and sanity testing?**
**Answer:**
- **Smoke Testing:** A preliminary test to check whether the most critical functionalities of the software are working after a new build or deployment.
  - **Example:** Checking if the application launches and basic features are functioning.
- **Sanity Testing:** A focused test to verify that a specific functionality or bug fix is working as expected after changes have been made.
  - **Example:** Verifying that a bug fix resolves the reported issue without breaking other parts.

---

### **14. What is a defect life cycle?**
**Answer:**  
The **Defect Life Cycle** refers to the journey of a defect from its identification until it is resolved. It involves various stages such as:
1. **New** – The defect is identified and reported.
2. **Assigned** – The defect is assigned to a developer or tester.
3. **Open** – The defect is being investigated.
4. **Fixed** – The defect has been fixed and is awaiting retesting.
5. **Retest** – The defect fix is tested.
6. **Closed** – The defect is resolved and closed.
7. **Reopened** – If the defect is not fixed properly, it is reopened.

---

### **15. What is the purpose of user acceptance testing (UAT)?**
**Answer:**  
**User Acceptance Testing (UAT)** is the final phase of testing conducted by the end-users to verify whether the software meets their business requirements and is ready for deployment. The purpose of UAT is to ensure that the software works in real-world scenarios and that the users are satisfied with its functionality.

---