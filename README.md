# QA Portfolio

**Aqsa Shoukat** | Entry level software tester (manual and basic API testing) | Faisalabad, Punjab, Pakistan
Open to remote and entry level roles

## About this repository

This repository holds the test reports I wrote while learning software testing. I test public demo websites by hand on my Android phone, and I also practiced sending API requests. Every report has the steps, the expected result, the actual result and screenshots as proof.

I am at the start of my testing career, so I want to be clear about what this is. These are practice projects on demo sites. I did not test a real company product, I did not use test automation, and I have not tested a native mobile app yet. Each report has a section called **What I did not cover** so you can see where the limits are.

## Reports

| Report | What I tested | Date | Result |
|---|---|---|---|
| [ParaBank](reports/ParaBank_Manual_Testing_Report.pdf) | Online banking demo: open account, transfer funds, bill pay, find transactions, update contact info, request loan | 6 Oct 2026 | 48 cases: 28 passed, 18 failed, 2 other |
| [OrangeHRM](reports/OrangeHRM_Manual_Testing_Report.pdf) | HR system demo: login and add employee | 17 Oct 2026 | 17 cases: 12 passed, 1 failed, 4 observations |
| [CURA Healthcare](reports/CURA_Healthcare_Mobile_Test_Report.pdf) | Appointment booking demo, exploratory testing on a phone | 16 Oct 2026 | 10 issues found |
| [Swagger Petstore API](reports/Swagger_Petstore_API_Testing_Report.pdf) | Pet endpoints of a public API, tested with Swagger UI | 18 and 19 Oct 2026 | 11 cases: 10 passed, 1 failed |
| [SauceDemo](reports/SauceDemo_Test_Report.pdf) | Online shop demo: login, products, cart and checkout | Sept 2026 | 20 cases: 20 passed |
| [Buggy Cars Rating](reports/BuggyCars_Bug_Report.pdf) | Car rating site: registration, login and comments | Sept 2026 | 7 defects: 1 Critical, 2 High, 3 Medium, 1 Low |
| [Buggy Cars in Jira](reports/BuggyCars_Jira_Tickets.pdf) | The same 7 bugs logged as Jira tickets | Sept 2026 | BCBT-1 to BCBT-7 |
| [Website status check](reports/Mini_Postman_Status_Check_Report.pdf) | Three GET requests to saucedemo.com with Mini Postman | Sept 2026 | 3 requests |

There is also a one page overview: [Portfolio Summary](00_Portfolio_Summary.pdf).

## Some of the problems I found

- **ParaBank:** a transfer of a negative amount (-20) was accepted and money moved the wrong way between the accounts. Transfers of 0 were also accepted.
- **Buggy Cars Rating:** an abusive comment was accepted and shown on the car page, and a one letter comment was accepted.
- **CURA Healthcare:** an appointment could be booked for a date in the past.
- **Swagger Petstore API:** the server accepted a pet with a status that is not one of the allowed values (available, pending or sold).
- **OrangeHRM:** the Employee Id that the form fills in by itself was often already taken, so a valid employee could not be saved. This is a demo site that many people use, so I listed it as a possible issue and not a sure bug.

## How I test

1. I explore the page first and write down what I see.
2. I try the normal flow, then wrong or unusual input: empty fields, letters in number fields, zero, negative numbers, very long text and spaces.
3. I save a screenshot for each result. The phone clock is visible in most of them.
4. I mark a result as an **observation** when I have no requirement to compare with, instead of calling it a bug.
5. I write down what I did not cover.

## Tools

- Android phone browser for all web testing
- Swagger UI and Mini Postman for API requests
- Jira for bug tickets
- Screenshots as evidence

## What I am learning next

- Testing mobile apps, not only websites in a phone browser
- Writing functional test cases from my exploratory notes
- Testing SauceDemo with the other demo users (problem_user, locked_out_user and others)
- Using Postman on a real API, including POST, PUT and DELETE requests
- Using AI tools such as Claude, Gemini and ChatGPT well in testing work

## A note on the documents

All testing was done by me, by hand, on my phone. I used AI tools to help with the layout and wording of these documents.

## Contact

LinkedIn: https://www.linkedin.com/in/
aqsa-shoukat-392707422
