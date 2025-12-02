# QA Exploratory Testing Project – Metrobi Platform

## Overview

This project contains the exploratory testing missions conducted for the Metrobi delivery platform. The main objective was to assess the platform's functionality, mobile responsiveness, and user experience across different modules.

## Tested Modules and Wiki Links

* **Deliveries** – [Mission 1 – Exploration of Deliveries Section](https://github.com/celiapaivab/metrobi-test/wiki/Mission-1-%E2%80%93-Exploration-of-Deliveries-Section)
* **Drivers** – [Mission 2 – Exploration of Drivers Section](https://github.com/celiapaivab/metrobi-test/wiki/Mission-2-%E2%80%93-Exploration-of-Drivers-Section)
* **Customers** – [Mission 3 – Exploration of Customers Section](https://github.com/celiapaivab/metrobi-test/wiki/Mission-3-%E2%80%93-Exploration-of-Customers-Section)
* **Settings** – [Mission 4 – Exploration of Settings Section](https://github.com/celiapaivab/metrobi-test/wiki/Mission-4-%E2%80%93-Exploration-of-Settings-Section)
* **Mobile** – [Mission 5 – Mobile Testing](https://github.com/celiapaivab/metrobi-test/wiki/Mission-5-%E2%80%93-Mobile-Testing)

## Tools Used

* **Browser DevTools** – Chrome for desktop and mobile emulation.
* **Manual exploratory testing** – Functional verification and user flows.

## Test Methodology

* Exploratory testing was applied to discover defects, layout issues, and potential UX improvements.
* Mobile responsiveness was checked using device emulation.
* All findings were documented in markdown format with observations, defects, and questions.

## Key Findings

* Some areas have layout issues on mobile devices, especially Delivery Settings.
* Most core functionalities (create/edit/cancel deliveries, add/edit users/customers/drivers) are working as expected.
* Delivery Rates allow special characters, large numbers, and negative numbers in "Per hour rate" fields.
* "Incoming Deliveries" list does not display created deliveries.

## Recommendations

To extend coverage and increase overall test quality, the following enhancements are recommended:

- **Automated UI Testing**  
  Suggested tools: Cypress, Playwright, Selenium

- **API Testing**  
  Suggested tools: Postman, Newman, Supertest

- **Performance Testing**  
  Suggested tools: Lighthouse, K6

- **Accessibility Testing**  
  Suggested tools: axe DevTools


## Author

Celia Bruno – QA Analyst and Tester
