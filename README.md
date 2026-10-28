# QA Portfolio

**Aqsa Shoukat** | Software tester (manual and basic API testing) | Faisalabad, Punjab, Pakistan | Open to remote roles

## About this repository

This repository holds the test reports I wrote while learning software testing. I test public demo websites and public Android apps by hand on my own phone, and I also practiced sending API requests. Every report has the steps, the expected result, the actual result and screenshots as proof.

I am at the start of my testing career, so I want to be clear about what this is. These are practice projects on demo sites and public apps. I did not test a company's own product, I did not use test automation, and so far I have tested three Android apps. Each report says what I did not cover, so you can see where the limits are.

## Reports

| Report | What I tested | Date |
| --- | --- | --- |
| [ParaBank](reports/ParaBank_Manual_Testing_Report_FINAL.pdf) | Online banking demo: open account, transfer funds, bill pay, find transactions, update contact info, request loan | 6 Oct 2026 |
| [OrangeHRM](reports/OrangeHRM_Manual_Testing_Report_FINAL.pdf) | HR system demo: login and add employee | 17 Oct 2026 |
| [CURA Healthcare](reports/CURA_Healthcare_Mobile_Test_Report_FINAL.pdf) | Appointment booking demo, exploratory testing on a phone | 16 Oct 2026 |
| [Swagger Petstore API](reports/Swagger_Petstore_API_Testing_Report_FINAL.pdf) | Pet endpoints of a public API, tested with Swagger UI | 18 and 19 Oct 2026 |
| [SauceDemo](reports/SauceDemo_Test_Report_FINAL.pdf) | Online shop demo: login, products, cart and checkout | Sep and Oct 2026 |
| [Buggy Cars Rating](reports/BuggyCars_Bug_Report_FINAL.pdf) | Car rating site: registration, login and comments | Sep 2026 |
| [Buggy Cars in Jira](reports/BuggyCars_Jira_Tickets.pdf) | The same 7 bugs logged as Jira tickets | Sep 2026 |
| [Website status check](reports/Mini_Postman_Status_Check_Report.pdf) | Three GET requests to saucedemo.com with Mini Postman | Sep 2026 |
| [Wikipedia Android app](reports/Wikipedia_Android_App_Test_Report.pdf) | Android app: search, reading articles, saving, rotation, airplane mode and Back button | 23 and 24 Oct 2026 |
| [Google Keep Android app](reports/Google_Keep_Android_App_Test_Report.pdf) | Android notes app: making, editing, deleting and searching notes, and notes staying after closing the app | Oct 2026 |
| [Daraz Android app](reports/Daraz_Android_App_Test_Report.pdf) | Android shopping app as a visitor: search, product page, options and quantity, login wall, airplane mode | Oct 2026 |

There is also a one page overview: [Portfolio Summary](reports/00_Portfolio_Summary.pdf).

## Mobile app testing

After testing websites, I started testing Android apps on my own phone, an Oppo A3 with Android 14. I used public apps and I only did what a normal user can do.

- **Wikipedia app.** I tested search with normal words, empty text, spaces, numbers, symbols and Urdu. I also tested reading, links, the Back button, Find in article, text size, saving articles, rotating the phone, airplane mode and sending the app to the background. I did not edit anything, I did not log in and I did not donate.
- **Google Keep.** I made, edited, deleted and searched notes, tried an empty note, a very long note and an Urdu note, and checked that the notes were still there after closing and opening the app. I wrote only test text in the notes.
- **Daraz.** I tested it as a visitor. I used search, the product page, the option and quantity panel and airplane mode. Adding to the cart needs a login, and because it is a real shop I did not log in, I did not place any order and I did not use my own details. So I could not test the cart, and the report says so.

I first wanted to test the Sauce Labs demo shop app, but it would not install on Android 14 because Google Play Protect blocked it, so I chose Daraz instead.

I did not find a real bug in these apps. I did write down small things a user could trip over, and I also wrote what I could not test and why.

## Some of the problems I found

- **ParaBank:** a transfer of a negative amount (-20) was accepted and money moved the wrong way between the accounts. Transfers of 0 were also accepted.
- **Buggy Cars Rating:** an abusive comment was accepted and shown on the car page, and a one letter comment was accepted.
- **CURA Healthcare:** an appointment could be booked for a date in the past.
- **Swagger Petstore API:** the server accepted a pet with a status that is not one of the allowed values (available, pending or sold).
- **OrangeHRM:** the Employee Id that the form fills in by itself was often already taken, so a valid employee could not be saved. This is a demo site that many people use, so I listed it as a possible issue and not a sure bug.

## How I test

1. I explore the page first and write down what I see.
2. I try the normal flow, then wrong or unusual input: empty fields, letters in number fields, zero, negative numbers, very long text and spaces.
3. On a phone I also try turning the phone, airplane mode, the Back button and leaving the app and coming back.
4. I save a screenshot for each result. The phone clock is visible in most of them.
5. I mark a result as an **observation** when I have no requirement to compare with, instead of calling it a bug.
6. I write down what I did not cover.

## Tools

- Android phone browser for web testing
- Android apps tested on my own phone (Wikipedia, Google Keep and Daraz)
- Swagger UI and Mini Postman for API requests
- Jira for bug tickets
- Screenshots as evidence

## What I am learning next

- Writing functional test cases from my exploratory notes
- Testing a shopping app where I can log in and test the cart (the Daraz test stopped at the login)
- Testing more mobile apps, including slow internet and low battery
- Testing SauceDemo with the other demo users (problem_user, performance_glitch_user, error_user and visual_user)
- Using Postman on a real API, including POST, PUT and DELETE requests
- Using AI tools such as Claude, Gemini and ChatGPT well in testing work

## A note on the documents

All testing was done by me, by hand, on my phone. I used AI tools to help with the layout and wording of these documents.

## Contact

LinkedIn: https://www.linkedin.com/in/aqsa-shoukat-392707422
