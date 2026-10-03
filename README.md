# 👩‍💻 Aqsa Shoukat — Manual QA Portfolio

**Aspiring Manual QA Analyst | Software Quality Assurance (Entry-Level)**

📍 Faisalabad, Pakistan | 🌐 Open to remote entry-level roles

🔗 LinkedIn: https://www.linkedin.com/in/aqsa-shoukat-392707422

---

## 📌 About This Portfolio

This repository contains my self-directed QA practice: test cases, test reports, bug reports and basic API testing.

All work was done on **public demo websites built for practice** (SauceDemo, Buggy Cars Rating and a public API), not on real company products. I use them to learn how to understand a product, explore it, find risks and document what I find.

---

## 🧭 How I Approach Testing

1. **Understand the product first**: who the user is and what they are trying to do.
2. **Exploratory testing**: explore freely, take notes, find scenarios and risks.
3. **Functional testing**: turn what I learned into structured test cases (EP, BVA, positive/negative, edge cases).
4. **Report clearly**: steps to reproduce, expected vs actual result, severity and screenshots.

---

## 📚 Testing Fundamentals I Work By

- **Testing everything is impossible.** I prioritize by risk: what would hurt the user or the business most if it broke?
- **Testing shows that bugs exist; it cannot prove there are none.**
- **EP and BVA** let me cover many inputs with fewer test cases.
- **Both positive and negative tests are needed**, because users do not always follow the happy path.
- **A good bug report** lets another person reproduce the problem without asking me questions.

---

## 🗂️ Projects

### 🐛 Project 1: Bug Tracking — Buggy Cars Rating (demo web app)

**Tool used:** Jira

Exploratory testing of the Buggy Cars Rating demo application. **7 bugs** were logged in Jira.

| Bug ID | Title |
|--------|-------|
| BCBT-1 | Abusive content allowed in comment field |
| BCBT-2 | Comment input box missing from car detail page |
| BCBT-3 | Register button hidden when mobile keyboard is open |
| BCBT-4 | Technical error message shown on duplicate registration |
| BCBT-5 | Registration form visible after successful login |
| BCBT-6 | Login field label is misleading on Registration page |
| BCBT-7 | Single character accepted as valid comment |

Each bug report includes steps to reproduce, expected vs actual results, severity, environment details and screenshots.

📄 Reports:
- [BuggyCars_Bug_Report.pdf](03-bug-reports/BuggyCars_Bug_Report.pdf)
- [Bug_Tracking_Portfolio.pdf](03-bug-reports/Bug_Tracking_Portfolio.pdf)

---

### ✅ Project 2: Manual Testing — Test Design and SauceDemo Practice

**2a. Login module test case design**

- Wrote **25 test cases** for a login page (email + password) in the standard format: ID, scenario, preconditions, steps, test data, expected result, actual result, status.
- Techniques used: EP, BVA, positive/negative testing, and UI checks.
- These test cases are written for a generic e-commerce login page, not for one specific website.
- **Status:** 14 test cases are marked completed and 11 are planned. Actual results (Pass/Fail) are not recorded yet. Executing them is part of my current improvement plan below.

**2b. SauceDemo test execution**

**Platform:** SauceDemo (a public practice site, not a real store)

- Tested **4 modules** (Login, Products, Cart, Checkout): **20 test cases, 18 passed, 2 failed**.
- Documented defects with reproduction steps and severity.

📄 Documents:
- [Login_Module_25_Test_Cases.pdf](01-test-cases/Login_Module_25_Test_Cases.pdf)
- [SauceDemo_Test_Summary_Report.pdf](02-test-reports/)

---

### 🔌 Project 3: API Testing — Postman (fundamentals)

- Practiced REST API testing with Postman: GET requests, status codes 200 and 404.
- Applied basic SQL queries for data validation.

📄 [API_Testing_Report.pdf](04-api-testing/API_Testing_Report.pdf)

---

## 🚧 Currently Improving (next 1–2 weeks)

- [ ] Execute the 25 login test cases on a real login page and record the actual results (Pass/Fail) with screenshots
- [ ] Adapt the login test cases to the real app being tested (for example, SauceDemo uses a username, not an email) and add missed scenarios such as the locked-out user
- [ ] Add exploratory testing session notes (what I explored, what I found, what risks I saw)
- [ ] Practice on demo apps from other industries (booking, HR, banking)
- [ ] Start mobile app testing
- [ ] Learn to use AI tools (Claude, Gemini, ChatGPT) effectively in QA work, for example to generate test ideas and then review and correct them myself

---

## 🛠️ Tools & Skills

| Category | Tools / Skills |
|----------|----------------|
| Bug Tracking | Jira |
| API Testing | Postman (Fundamentals) |
| Version Control | Git, GitHub |
| Testing Types | Manual, Functional, Exploratory (learning), EP, BVA, Edge-Case |
| Documentation | MS Excel, Google Sheets, MS Word |
| Database | SQL (Basic: Query & Validation) |
| Browser Tools | Chrome DevTools |
| Programming | Java (OOP) |

---

## 📁 Repository Structure

```
QA-Portfolio/
├── README.md
├── 01-test-cases/
│   └── Login_Module_25_Test_Cases.pdf
├── 02-test-reports/
│   └── SauceDemo_Test_Summary_Report.pdf
├── 03-bug-reports/
│   ├── BuggyCars_Bug_Report.pdf
│   └── Bug_Tracking_Portfolio.pdf
└── 04-api-testing/
    └── API_Testing_Report.pdf
```

---

## 📬 Contact

- 📧 aqsashoukatl626@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/aqsa-shoukat-392707422
- 🌍 Open to remote entry-level QA opportunities

*This portfolio is actively maintained and updated as I continue building my QA skills.*
