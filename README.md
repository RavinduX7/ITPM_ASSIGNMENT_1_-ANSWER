# IT3040 ITPM Assignment 1 – Playwright Automation

This repository contains Playwright test automation for the Singlish → Sinhala conversion website:
https://www.swifttranslator.com

## Prerequisites
- Node.js (LTS recommended)
- npm (comes with Node.js)

## Setup
1. Download/clone this repository.
2. Open a terminal inside the project folder.
3. Install dependencies:
   npm install
4. Install Playwright browsers:
   npx playwright install

## Run tests
- Run all tests:
  npx playwright test

- Run with HTML report:
  npx playwright test --reporter=html
  npx playwright show-report
