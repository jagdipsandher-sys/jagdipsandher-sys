# Jack Sandher

Hi, I'm Jack. I'm the Managing Director of Top Secret Imports in Sydney. I've spent 18 years in Australian vehicle compliance and importing, running operations across five states and Japan with bases in Yokohama, Nagoya and Osaka.

My background is in software. I hold a Bachelor of Science in Computing and an MBA from the University of Technology Sydney, and I started my career as a software engineer at CSC and Thales. Since 2008 I've built Top Secret Imports into a national operation with more than 50 staff, and that business experience sits on top of the technical one. I understand the code and I understand the commercial reason for building it.

Over the last few years I've built the software that runs our business. I scope it, design it and build it, and bring in developers where it makes sense. Everything below is in daily use.

The source code stays private because it runs a live business and holds customer data. I'm more than happy to walk you through any of it on a screen share.

---

## What I've built

### 1. TSI MOS, Management Operating System
One screen that answers one question: what needs my attention today?

1. Pulls live data from Rover, Xero, our sales sheets and the Market Radar automatically. No manual data entry.
2. Refreshes twice a day and emails the team a morning summary at 7:30am.
3. Every tile shows how old its data is, so a broken feed shows up straight away instead of hiding.
4. Financial figures sit behind a passcode and never go out in the email.

**Stack:** Python, GitHub Actions, Cloudflare Workers, Xero API

### 2. SEVS Eligibility Checker
Enter a Japanese chassis number and it identifies the vehicle and works out whether it's eligible for import under SEVS. It also translates Japanese auction sheets and screens them for eligibility.

Built so the team and our customers can screen a car before it's bought, not after it lands.

**Stack:** HTML, JavaScript

### 3. TSI Market Radar
Every night it visits the websites of Australia's imported vehicle dealers, clients and competitors, counts the stock each one has for sale and publishes a dashboard by state with daily, weekly and monthly movement.

It runs on GitHub's servers, so nobody's laptop needs to be on, and it handles sites that hide their stock behind scripts.

**Stack:** Python, Playwright, GitHub Actions, GitHub Pages

### 4. TSI Valuations and Premium Valuations
A vehicle valuation engine, live at valuations.topsecretimports.com.au. The same engine now also runs a separate company's legal valuations service. Built once, used twice.

**Stack:** TypeScript, Next.js, Cloudflare

### 5. Katana, TSI Operating System
Our in house compliance and operations platform. It tracks every vehicle through compliance and is where our stock days and yard data come from.

**Stack:** PHP, Laravel

---

## Also built

1. **TSI Website:** designed, built and deployed the new topsecretimports.com.au. I control deploys, so it gets improved while it's live.
2. **Model Reports:** WordPress platform for our model report products, built with an external developer.
3. **BAWA Fight Radar:** a personal project. A weekly email and web page covering UFC, boxing, NRL, F1 and more, all in Sydney time.

---

## How I work

1. Start with the business problem, not the tech.
2. Automate the data so nobody types it twice.
3. Be honest when data is stale or missing. Never guess.
4. Ship it, use it every day, then keep improving it while it's live.

---

## Tools

Python, TypeScript, PHP, JavaScript, Next.js, Laravel, WordPress, GitHub Actions, Cloudflare, Xero API, Playwright, Claude

---

## Get in touch

[LinkedIn](https://www.linkedin.com/in/jack-sandher-b7771a54/)

Happy to jump on a quick call if that's easier.
