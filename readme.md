# 16 Days Activism 2026 — README

1. [About the Project](#about-the-project)
2. [The Problem](#the-problem)
3. [The Solution](#the-solution)
    1. [Educate — "The Issue"](#educate)
    2. [Support — "Get Help"](#support)
    3. [Act — "Take Action"](#act)
4. [Technologies Used](#technologies-used)
5. [Project Structure](#project-structure)
6. [Purpose](#purpose)
7. [Key Features](#key-features)
8. [Getting Started](#getting-started)
    1. [Clone the repository and install dependencies (Bootstrap Icons via npm):](#clone)
    2. [Build the Tailwind CSS (if modifying styles):](#build)
    3. [Open `index.html` in a browser, or serve the folder with any static server:](#open)
9. [Campaign Information](#campaign-information)

---
# About the Project

**16 Days Activism 2026** is a multi-page awareness website built for the 16 Days of Activism against Gender-Based Violence campaign, running **from 25 November to 10 December 2026**. The site serves as a digital platform to educate the public, provide support resources for survivors, and encourage community action to end gender-based violence (GBV).
The campaign is built around the message: *"A future free from violence starts with US."*

# The Problem

Gender-based violence affects millions of women and girls worldwide. Despite being a widespread human rights violation, it often remains:

* **Normalized or dismissed** in communities through harmful attitudes, jokes, and excuses.

* **Under-reported**, because survivors fear stigma, retaliation, or not being believed.

* **Poorly understood**, with many people unaware of the facts, their rights, or where to seek help.

* **Unpunished**, as impunity allows violence to continue across generations.

Many survivors do not know where to turn for support, and bystanders often lack the knowledge or confidence to intervene or challenge harmful behavior.


# The Solution

This website offers a centralized, accessible, and bilingual-friendly resource hub that addresses the problem on three fronts:

<a id="educate"></a>

- Educate — "The Issue"


The homepage explains why the campaign matters, presenting key facts, objectives, and a clear message that violence is never love and real strength means respect. It challenges harmful attitudes and promotes equality.

<a id="support"></a>

- Support — "Get Help"

A dedicated page provides survivors with immediate, actionable support:

* Emergency numbers **(Police 19, SAMU 15)** for people in immediate danger.

* A **24/7 listening service (8350)**.

* Information on women's support centres, psychological help, legal assistance, safe accommodation, and medical care.

* A step-by-step guide on how to get help and an FAQ section addressing common concerns (anonymity, children's services, etc.).

<a id="act"></a>

- Act — "Take Action"

A page empowering individuals and organizations to contribute:

* Concrete actions for individuals (challenge violence, promote respect, educate, support survivors).

* Partnership opportunities for organizations (financial support, technical assistance, awareness initiatives, strategic partnerships).

The site also includes **multilingual support (English, French, Arabic)** and is fully responsive for mobile and desktop.

## Technologies Used

| Category | Technology | Description |
| :--- | :--- | ---: |
| **Markup** | HTML5 | Semantic, accessible structure |
| **Styling** | [Tailwind CSS v4](https://tailwindcss.com/) | Utility-first CSS framework with `@theme` config |
| **Icons** | [Bootstrap Icons](https://icons.getbootstrap.com/) | Lightweight vector icon library |
| **Typography** | Google Fonts | Inter (sans-serif) & Poppins (display) |
| **Architecture** | Mobile-First | Responsive breakpoints (`sm`, `md`, `lg`) & Flex/Grid |
| **Interactivity** | Native HTML | `<details>` / `<summary>` accordions (no JS needed) |
| **Tooling** | Tailwind CLI | Compiled production CSS (`output.css`) |
| **Assets** | WebP | Performance-optimized visual imagery |


## Project Structure
```text
/
├── index.html                  # Homepage — campaign intro & the issue
├── public/
│   ├── css/
│   │   ├── output.css          # Compiled Tailwind build
│   │   └── index.css           # Custom styles + Tailwind imports
│   ├── image/                  # Campaign imagery (WebP)
│   └── page/
│       ├── getHelp.html        # Survivor support & resources
│       └── takeAction.html     # Individual & organizational action
├── node_modules/
│   └── bootstrap-icons/        # Icon font
└── README.md
```

## Purpose

The project's purpose is to amplify the 16 Days of Activism campaign by:

1. Raising awareness about gender-based violence and its root causes.

2. Providing immediate, trustworthy support pathways for survivors and those at risk.

3. Mobilizing communities — individuals, companies, and institutions — to take concrete action.

4. Promoting a culture of respect, equality, and zero tolerance for violence.

It is designed to be fast, accessible, and usable on any device, ensuring that someone in crisis can find emergency numbers within seconds.

## Key Features

✅ Sticky, blurred navigation with active-page indicators

✅ Responsive mobile menu with language switcher (EN · FR · AR)

✅ Eye-catching hero sections with gradient overlays and image masks

✅ Emergency contact cards prominently displayed on the Get Help page

✅ Accessible FAQ accordion using native ``<details>`` elements

✅ Visual action cards linking to related content

✅ Consistent footer with quick links, contact info, and social media

✅ Custom design tokens via Tailwind v4 ``@theme`` (brand colors, fonts, shadows)

## Getting Started

<a id="clone"></a>

1. Clone the repository and install dependencies (Bootstrap Icons via npm):

```bash
npm install bootstrap-icons
```
<a id="build"></a>

2. Build the Tailwind CSS (if modifying styles):

```bash
npx @tailwindcss/cli -i ./public/css/index.css -o ./public/css/output.css --watch
```
<a id="open"></a>

3. Open ``index.html`` in a browser, or serve the folder with any static server:

```bash
npx serve .
```

>Note: The project also loads Tailwind's browser CDN for on-the-fly ``@theme`` processing, but the >production styles live in ``output.css``.

## Campaign Information

* Campaign: 16 Days of Activism against Gender-Based Violence

* Dates: 25 November – 10 December 2026

* Hashtags: ``#16Day``s · ``#OrangeTheWorld``

* Contact: contact@gmail.com · +212 665241236

---

Together for a safer, fairer world. 🧡

