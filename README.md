# E-Commerce Website Manual Testing Project

![Testing](https://img.shields.io/badge/Testing-Manual-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Web-orange)

## 📋 Project Overview

This project demonstrates comprehensive manual testing of a generic public e-commerce website, focusing on critical user journeys and core shopping functionalities. The testing validates the complete guest user experience from product discovery through checkout.

## 🎯 Objectives

- Validate core shopping flow for guest users
- Ensure seamless user experience across critical functionalities
- Identify and document defects with detailed reproduction steps
- Verify UI consistency and usability standards
- Test end-to-end workflows for e-commerce operations

## 🔍 Testing Scope

### In Scope
- Homepage functionality and navigation
- Product search with keyword functionality
- Product listing page (PLP) display and filters
- Product detail page (PDP) information
- Shopping cart management
- Guest checkout process
- UI/UX validation

### Out of Scope
- Payment gateway integration
- User account creation and login
- Admin panel functionality
- Backend systems
- Email notifications
- Third-party integrations

## 🧪 Test Scenarios

| Scenario ID | Module | Description | Priority |
|------------|--------|-------------|----------|
| TS_01 | Search | Search product using keyword | High |
| TS_02 | Product Listing | View product details from listing page | High |
| TS_03 | Shopping Cart | Add product to cart | High |
| TS_04 | Shopping Cart | Update product quantity in cart | Medium |
| TS_05 | Checkout | Complete guest checkout flow | High |

## 🛠️ Test Environment

**Browser:** Google Chrome (Latest Version)

**Operating System:** Windows 10

**Additional Browsers Tested:**
- Mozilla Firefox (Latest Version)
- Microsoft Edge (Latest Version)

**Test Data:** Publicly available products on the e-commerce website

## 📊 Testing Approach

### Test Design Techniques
- Equivalence Class Partitioning
- Boundary Value Analysis
- Decision Table Testing
- State Transition Testing
- Use Case Testing
- Error Guessing
- Exploratory Testing

### Testing Types Performed
- **Functional Testing** - Verify feature functionality
- **UI Testing** - Validate interface elements and layout
- **Smoke Testing** - Quick validation of critical features
- **Sanity Testing** - Focused testing on bug fixes
- **Regression Testing** - Ensure existing functionality integrity
- **Usability Testing** - Evaluate user-friendliness

## 📁 Project Structure

```
e-commerce-manual-testing/
│
├── Test_Plan/
│   └── Test_Plan_Ecommerce_Manual_Testing.docx
│
├── Test_Artifacts/
│   └── Test_Artifacts.xlsx
│
├── Test_Cases/
│   └── Test_Cases_Ecommerce.xlsx
│
├── Test_Execution/
│   └── Test_Execution_Report.xlsx
│
├── Defect_Reports/
│   └── Defect_Log.xlsx
│
├── Screenshots/
│   ├── Homepage/
│   ├── Product_Listing/
│   ├── Cart/
│   ├── Checkout/
│   └── Defects/
│
└── README.md
```

## 📝 Test Deliverables

1. **Test Plan Document** - Comprehensive testing strategy and approach
2. **Test Scenarios** - High-level test scenarios covering all functionalities
3. **Test Cases** - Detailed test cases with step-by-step instructions
4. **Test Execution Report** - Test case execution status with pass/fail results
5. **Defect Report** - Comprehensive defect log with severity and priority
6. **Test Summary Report** - Final testing summary with metrics
7. **Screenshots** - Visual evidence of test execution and defects

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| Google Chrome | Primary browser for test execution |
| Microsoft Excel | Test case management and defect tracking |
| Windows Snipping Tool | Screenshot capture for documentation |
| Microsoft Word | Test plan and report documentation |

## 👥 Team Structure

- **Test Lead:** TL_ID_001 - Overall test planning, coordination, and reporting
- **Tester 1:** Search and product listing testing
- **Tester 2:** Shopping cart functionality testing
- **Tester 3:** Checkout process and UI testing

## ⚠️ Risks and Mitigations

| Risk | Mitigation Strategy |
|------|---------------------|
| Limited testing timeframe | Prioritize critical test cases; focus on high-risk areas |
| Website downtime | Document issues; work on test documentation during downtime |
| Incomplete requirements | Make assumptions based on industry standards; document clearly |
| Browser compatibility | Primary testing on Chrome; note browser-specific issues |
| Limited testing tools | Maximize use of available free tools and browser features |

## 📅 Test Schedule

| Activity | Timeline |
|----------|----------|
| Test Plan Creation | January 23, 2026 |
| Test Case Creation | January 23, 2026 |
| Test Execution & Defect Logging | January 24, 2026 |
| Test Summary Report | January 24, 2026 |

## 🎓 Key Learnings

- Importance of detailed test planning and documentation
- Effective use of test design techniques for comprehensive coverage
- Critical thinking in identifying edge cases and potential issues
- Systematic approach to defect documentation and tracking
- Balancing thoroughness with time constraints

## 📈 Test Metrics

*(To be updated after test execution)*

- **Total Test Cases:** 10
- **Test Cases Executed:** 9
- **Pass Rate:** 90%
- **Defects Found:** 1
- **Critical/High Severity Defects:** 0
- **Test Coverage:** 90%

## 🔗 Test Execution Summary

### Entry Criteria
- Test plan approved and documented
- Test cases created and reviewed
- Test environment accessible and stable
- Test data prepared

### Exit Criteria
- All planned test cases executed
- Critical defects documented
- Test reports completed
- Final approval obtained

## 💡 Assumptions

- The e-commerce website is publicly accessible and stable
- Products are real and available for testing
- Payment processing is mocked (no actual purchases made)
- Internet connectivity remains stable during testing
- Website functionality remains consistent during test period

## 📄 Documentation Standards

All test artifacts follow industry-standard formats:
- Test cases include: Test Case ID, Description, Preconditions, Test Steps, Expected Results, Actual Results, Status
- Defects include: Defect ID, Title, Severity, Priority, Steps to Reproduce, Expected vs Actual, Screenshots, Environment Details

## 🚀 How to Use This Repository

1. Review the **Test Plan** document for complete testing strategy
2. Examine **Test Cases** for detailed test scenarios
3. Check **Test Execution Report** for results and status
4. Review **Defect Reports** for issues identified
5. View **Screenshots** folder for visual evidence

## 📧 Contact

For any questions or clarifications about this testing project, please feel free to reach out.

---

## 🙏 Acknowledgments

This project was created as a demonstration of manual testing skills and best practices in software quality assurance.

---

**Note:** This is a personal portfolio project created to showcase manual testing expertise and documentation capabilities. All names, teams, and scenarios are for demonstration purposes.

---

## 📊 Project Status

**Current Status:** ✅ Testing Completed

**Next Steps:**
- [ ] Generate test execution report
- [ ] Prepare final test summary

---

*Last Updated: January 24, 2026*
