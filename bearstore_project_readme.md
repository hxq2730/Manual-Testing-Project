# 🛒 BearStore E-Commerce Testing Project

## 📌 Project Information

**Application Under Test:** BearStore E-Commerce Platform  
**URL:** https://bearstore-testsite.smartbear.com/  
**Project Duration:** [September 2025 - December 2025]  
**Testing Type:** Manual Functional Testing  
**Methodology:** Agile/Scrum  
**My Role:** Manual QA Tester  

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Testing Scope](#testing-scope)
- [Test Environment](#test-environment)
- [Testing Activities](#testing-activities)
- [Test Deliverables](#test-deliverables)
- [Key Metrics](#key-metrics)
- [Key Learnings](#key-learnings)
- [Tools Used](#tools-used)

---

## 🎯 Project Overview

BearStore is an e-commerce web application that allows users to browse products, manage shopping carts, and complete purchases. This project involved comprehensive manual testing to ensure the platform meets functional requirements and provides a smooth user experience.

### Business Context
- **Industry:** E-Commerce / Retail
- **Target Users:** Online shoppers
- **Key Features:** Product browsing, cart management, user accounts, checkout process
- **Platforms Tested:** Web application

### Project Objectives
✅ Validate all functional requirements  
✅ Ensure smooth user workflows end-to-end  
✅ Identify and report defects before production  
✅ Ensure data integrity across the application  

---

## 🔍 Testing Scope

#### 1. User Management Module
- User Registration with email validation
- Login/Logout functionality
- Password reset functionality
- User profile management
- Session management

#### 2. Product Catalog Module
- Product listing and display
- Product search functionality
- Category-based filtering
- Sorting options (price, name)
- Product detail page
- Product images and descriptions
- Product compare

#### 3. Shopping Cart Module
- Add products to cart
- Update product quantities
- Remove items from cart
- Cart persistence across sessions
- Cart total calculation
- Empty cart functionality

#### 4. Checkout Process Module
- Billing information form
- Shipping address validation
- Payment method selection
- Order review page
- Order confirmation

#### 5. Order Management Module
- Order history viewing
- Order details display
- Order status tracking

#### 6. Cross-Cutting Concerns
- UI/UX consistency
- Form validations
- Error messages

---

## 🖥️ Test Environment

### Browsers Tested
| Browser | Version | OS |
|---------|---------|-----|
| Google Chrome | Latest | Windows 10 |
| Microsoft Edge | Latest | Windows 10 |

---

## ✅ Testing Activities

### Test Planning & Design
1. **Requirements Analysis**
   - Reviewed application features and user workflows
   - Identified testable requirements
   - Created Requirements Traceability Matrix (RTM)

2. **Test Case Design**
   - Covered positive, negative, and edge case scenarios
   - Total: **90+ test cases** designed

3. **Test Data Preparation**
   - Created test user accounts
   - Prepared valid and invalid input data sets
   - Set up test products for different scenarios

### Test Execution

#### Initial Testing (Functional)
- **Focus:** Core functionality validation
- **Test Cases Executed:** 92
- **Duration:** 2 weeks
- **Pass Rate:** 91%
- **Bugs Found:** 8

#### Final Regression
- **Focus:** Complete regression before release
- **Test Cases Executed:** 104
- **Duration:** 1 week
- **Pass Rate:** 98%
- **Bugs Found:** 2 (minor)

### Defect Management
- Logged all bugs in Jira with detailed information:
  - Clear title and description
  - Steps to reproduce
  - Expected vs Actual results
  - Screenshots
  - Environment details
  - Severity and Priority classification
- Tracked bug lifecycle from Open → In Progress → Resolved → Closed

---

## 📂 Test Deliverables

### 1. Test Cases
Comprehensive test case documentation covering all modules:

| Module | Test Cases | File |
|--------|------------|------|
| User Management | 58 | [User_Management_TestCases.xlsx](./Test-Cases/User_Management_TestCases.xlsx) |
| Product Catalog | 21 | [Product_Catalog_TestCases.xlsx](./Test-Cases/Product_Catalog_TestCases.xlsx) |
| Shopping Cart | 4 | [Shopping_Cart_TestCases.xlsx](./Test-Cases/Shopping_Cart_TestCases.xlsx) |
| Checkout Process | 5 | [Checkout_Process_TestCases.xlsx](./Test-Cases/Checkout_Process_TestCases.xlsx) |
| Order Management | 4 | [Order_Management_TestCases.xlsx](./Test-Cases/Order_Management_TestCases.xlsx) |
| **Total** | **92** | - |

**Test Case Structure:**
- Test Case ID
- Feature
- Test Case Name
- Objectives
- Preconditions
- Test Scripts
- Test Data
- Expected Result
- Actual Result
- Status (Pass/Fail)
- Priority (High/Normal/Low)
- Comments

### 2. Bug Reports
Detailed defect documentation with reproduction steps:

| Severity | Count | Status |
|----------|-------|--------|
| Critical | 2 | 1 Fixed, 1 Deferred |
| High | 2 | 2 Open |
| Medium | 1 |  1 Open |
| Low | 1 | 1 Deferred |
| **Total** | **6** | **1 Fixed, 3 Open, 2 Deferred** |

**Bug Report Files:**
- [Bugs_Report.xlsx](./Bug-Reports/Bugs_Report.xlsx)
- [Bug_Screenshots/](./Bug-Reports/Bug_Screenshots/) - Visual evidence

**Bug Report Template Included:**
- Bug ID
- Title
- Module/Feature
- Severity & Priority
- Environment
- Pre-conditon
- Steps to Reproduce
- Expected Result
- Actual Result
- Screenshots/Attachments
- Status
- Comments

### 3. Test Reports

#### Test Execution Summary
- [Test_Execution_Summary.xlsx](./Test-Reports/Test_Execution_Summary.xlsx)
- [Executive_Summary.pdf](./Test-Reports/Executive_Summary.pdf)
- [Zephyr_Cycle_Execution.pdf](./Test-Reports/Zephyr_Cycle_Execution.pdf)


### 4. Evidence & Screenshots

Visual documentation from Jira and Zephyr:

| Screenshot | Description |
|------------|-------------|
| [Jira_Dashboard.png](./Evidence/Jira_Dashboard.png) | Bug tracking dashboard showing defect distribution |
| [Zephyr_Test_Cycles.png](./Evidence/Zephyr_TestCycles.png) | Test cycle execution progress in Zephyr |
| [Zephyr_Traceability_Matrix.pdf](./Evidence/Zephyr_Traceability_Matrix.pdf) | Requirements to test cases mapping |


---

## 📊 Key Metrics

### Test Coverage
- **Overall Coverage:** 95%
- **Critical Features Coverage:** 100%
- **High Priority Features:** 98%
- **Medium Priority Features:** 92%

### Defect Metrics
- **Total Defects Found:** 6
- **Critical Defects:** 2 (33.3%)
- **High Severity:** 2 (33.3%)
- **Medium Severity:** 1 (16.6%)
- **Low Severity:** 1 (16.6%)
- **Defect Density:** 0.07 defects per test case

### Test Execution Metrics
- **Total Test Cases:** 92
- **Test Cases Executed:** 92 (14 cycles)
- **Cycle 1 Pass Rate:** 100%
- **Cycle 2 Pass Rate:** 100%
- **Cycle 3 Pass Rate:** 75%
- **Cycle 4 Pass Rate:** 100%
- **Cycle 5 Pass Rate:** 85%
- **Cycle 6 Pass Rate:** 100%
- **Cycle 7 Pass Rate:** 100%
- **Cycle 8 Pass Rate:** 88%
- **Cycle 9 Pass Rate:** 100%
- **Cycle 10 Pass Rate:** 90%
- **Cycle 11 Pass Rate:** 83%
- **Cycle 12 Pass Rate:** 67%
- **Cycle 13 Pass Rate:** 100%
- **Cycle 14 Pass Rate:** 100%
- **Average Execution Time:** ~30 minutesd per cycle

---

## 🎯 Key Achievements

✅ **Critical Bug Prevention**
- Identified 2 critical bugs in checkout flow before UAT
- Prevented potential revenue loss from payment processing issues
- Found cart calculation errors that could impact customer trust

✅ **High Test Coverage**
- Achieved 95% overall test coverage
- 100% coverage on critical business flows
- Comprehensive cross-browser validation

✅ **Quality Improvement**
- Reduced defect leakage to UAT by thorough testing
- Improved test documentation standards for the team
- Contributed to 98% pass rate in final regression

✅ **Process Efficiency**
- Created reusable test cases for future regression cycles
- Developed comprehensive test data sets
- Established clear bug reporting standards

---

## 💡 Key Learnings


📚 **Technical Skills**
- Improved test case design using structured techniques
- Enhanced bug reporting with clear reproduction steps
- Better understanding of e-commerce workflows and edge cases

📚 **Tools & Processes**
- Advanced Jira/Zephyr features for test management
- Excel formulas for test metrics and reporting
- Efficient test execution strategies


📚 **Domain Knowledge**
- E-commerce business flows and user behavior
- Common payment and checkout issues
- Importance of cart and session management

---

## 🛠️ Tools Used

| Tool | Purpose | Usage |
|------|---------|-------|
| **Jira** | Project Management & Bug Tracking | Created and tracked 6+ bugs with detailed information |
| **Zephyr Scale** | Test Management | Managed 90+ test cases, executed 14 test cycles |
| **Microsoft Excel** | Test Documentation & Reporting | Documented test cases, created metrics dashboards |
| **Chrome DevTools** | Browser Debugging | Inspected elements, checked console errors, network calls |
| **Snipping Tool** | Screenshots | Captured bug evidence and UI issues |

---

## 📈 Test Coverage Matrix

### Feature Priority vs Test Coverage

| Feature | Priority | Test Cases | Coverage |
|---------|----------|------------|----------|
| Checkout Flow | Critical | 5 | 70% |
| Shopping Cart | Critical | 4 | 70% |
| User Login | Critical | 10 | 100% |
| Product Search | High | 6 | 80% |
| Product Filtering | High | 7 | 70% |
| User Registration | Medium | 16 | 100% |
| Order History | Medium | 4 | 70% |

---

## 🔗 Related Links

- **Application URL:** https://bearstore-testsite.smartbear.com/

---

## 📞 Questions or Feedback?

If you have any questions about this project or would like to discuss testing approaches:

📧 Email: hoxuanquangqt@gmail.com  
💼 LinkedIn: [https://www.linkedin.com/in/hoxuanquang/](URL)

---

## 📝 Project Status

**Current Status:** ✅ Completed  
**Last Updated:** January 2026