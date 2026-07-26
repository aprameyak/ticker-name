# StockTickerInfo

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white&style=for-the-badge)

## About

**StockTickerInfo** is a desktop utility that lets users look up a stock's full company name by entering its ticker symbol. Built with **Python**, it provides a **Tkinter** GUI for input and uses **Selenium WebDriver** to scrape the corresponding company name from the web, displaying the result back in the window without leaving the app.

## Features

- Simple Tkinter GUI with a text field for ticker symbol input and a submit button
- Selenium WebDriver automates a Chrome browser to scrape the company name for the entered ticker
- Displays the resolved company name directly in the GUI after submission
- Lightweight single-file application with no external API keys required
- Headless-friendly Chrome automation via ChromeDriver

## Technology Stack

- **Language**: Python
- **GUI**: Tkinter
- **Web Scraping**: Selenium WebDriver, ChromeDriver
