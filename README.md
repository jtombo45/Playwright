# Playwright QA Automation Case Study

This repository was created as part of a **take-home interview assignment** for a QA role, but more importantly, as a personal learning project to explore **QA testing**, **web automation**, and how tools like **Selenium** and **Playwright** operate in real-world scenarios.

While Selenium is a popular automation tool, I chose to leverage **Playwright** due to its modern API and ease of setup — but the core concepts are transferable between both tools. This repo serves as a case study for anyone looking to understand automated browser testing and web scraping fundamentals.

---

## 🚀 Project Overview

The goal of this project is to:
- Use **Playwright** to automate the extraction of the latest **100 articles** from the [YCombinator Hacker News](https://news.ycombinator.com/) website.
- Overcome the pagination limitation where only **30 articles** are displayed per page.
- Demonstrate efficient, reliable scraping techniques within a QA automation framework.

This solution simulates what you'd typically build using Selenium, showcasing how automated browser tasks can be structured for both **testing** and **data extraction** purposes.

🎥 **Walkthrough Video:**  
[Watch on Loom](https://www.loom.com/share/be90f9920f64430dba7ef0fbd4b73771)

---

## 🛠️ Prerequisites

Ensure the following are installed on your machine:

### 1. [Node.js](https://nodejs.org/en)
Node.js is a JavaScript runtime that allows you to run JavaScript outside the browser — essential for running Playwright scripts.

### 2. [Visual Studio Code](https://code.visualstudio.com/)
A lightweight, versatile IDE to develop and run your automation scripts.

### 3. [Playwright](https://playwright.dev/)
An open-source automation library for browser testing and scraping, supporting Chromium, Firefox, and WebKit.

---

## ⚡ Installation

Navigate to your project folder and initialize Playwright:

```bash
npm init playwright@latest
```

## ▶️ Running the Scraper

To execute the automation and watch it interact with the browser:

```bash
npx playwright test --headed
```
The --headed flag allows you to see the browser in action as Playwright navigates pages and extracts article data.

## 📚 Why This Repo Exists
- ✅ To learn and apply QA automation principles inspired by Selenium workflows.
- ✅ To explore browser automation for both testing and scraping purposes.
- ✅ To document a real-world challenge (pagination handling, dynamic content extraction).
- ✅ For others interested in understanding how tools like Selenium & Playwright can automate repetitive browser tasks.

Feel free to fork this repo and adapt it for your own QA or scraping needs!

## 🔗 Links
- GitHub Repo: Playwright QA Automation
- Playwright Docs: https://playwright.dev/
- Selenium Reference: https://www.selenium.dev/
- YCombinator Hacker News: https://news.ycombinator.com/
