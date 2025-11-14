# GoIT Markup Homework #1: HTML Structure

## Description of the Assignment

This repository contains the solution for GoIT Markup Homework #1. The primary goal of this assignment was to create the fundamental HTML structure for the "WebStudio" homepage based on the provided layout.

The key constraint for this task was to use **only semantic HTML5 tags** to build the page skeleton. **No CSS styling** was applied. The entire focus was on correct markup, a logical document outline (header, main, footer), and accessibility basics (like `alt` attributes and a single `<h1>`).

---

## 🧾 Key Structural Elements

The following semantic structure was implemented according to the project requirements:

### General Page Structure

* The document follows a standard semantic layout: **`<header>`**, **`<main>`**, and **`<footer>`**.
* The root `<html>` tag includes the `lang="en"` attribute.
* The code successfully passes the **W3C HTML validator** without errors.

### Header (`<header>`)

* Contains the main navigation (`<nav>`) element.
* Includes the **"WebStudio" logo** as a text-based link (`<a>`) pointing to `./index.html`.
* Features a main menu (`<ul>`) with three navigation links: Studio, Portfolio, and Contacts.
* Includes a contact block (`<address>`) with email (`mailto:`) and phone (`tel:`) links, which is correctly placed *outside* the `<nav>` element.

### Main Content (`<main>`)

The main content is divided into three distinct sections:

1.  **Hero Section:** Contains the main page title (`<h1>`) "Effective Solutions for Your Business" and an "Order Service" button (`<button type="button">`).
2.  **Features Section:** Includes a visually-hidden `<h2>` (for screen readers) and a `<ul>` listing four company features (Strategy, Punctuality, Diligence, Technologies). Each feature is structured with an `<h3>` and a `<p>`.
3.  **"Our Team" Section:** Contains a visible `<h2>` ("Our Team") and a `<ul>` of four team members. Each list item (`<li>`) includes an `<img>` (with `alt` and `width` attributes), an `<h3>` (Name), and a `<p>` (Role).

### Footer (`<footer>`)

* Includes a secondary "WebStudio" logo link, identical to the header's.
* Contains a paragraph (`<p>`) with the company's closing statement.

---

## 🚀 Live Page

The project is hosted on GitHub Pages. You can view the live (un-styled) result here:

**[https://idziamko.github.io/goit-markup-hw-01/]**
