# Hi, I'm Mustafa

**I build software for the people behind the counter.**

Final-year BSc (Hons) Computing Systems student at Ulster University London, open to 2027 graduate software and backend roles. Python, FastAPI and PostgreSQL.

I have two apps in real use by paying businesses: a stock and ordering app for a London restaurant, and a food-safety exam app in 11 languages. AI coding tools write a lot of my code. I own the requirements, design decisions, testing and security checks, and I test everything with the people who actually use it.

Portfolio: [ghulam-mustafa-ms.vercel.app](https://ghulam-mustafa-ms.vercel.app) · LinkedIn: [ghulam-mustafa-41807b281](https://linkedin.com/in/ghulam-mustafa-41807b281) · Email: ghulammustafa99922@gmail.com

---

## What I've built

### Amigos Orders · stock and supplier ordering web app
*Client: Amigos Burgers & Shakes, Harrow · Sep 2026 to present · in live use*

Staff used to spend 15 to 20 minutes after closing writing supplier orders by hand on WhatsApp. I mapped that process with the team and built a mobile-first app that turns their stock counts into orders for 8 suppliers, each with its own order days and cut-off times. Ordering now takes about 5 minutes.

- Suggests order quantities from past orders and shows them beside the staff amounts
- Manager approval, added after a cover shift nearly doubled an order
- Food-safety records with inspection-ready PDF and Excel exports, plus phone reminders before supplier cut-offs
- Security audit before release: server-side role checks, CSRF protection, hashed PINs, login lockout, strict Content Security Policy
- 210 automated tests run on GitHub Actions for every change

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL (Neon)` `Vercel` `pytest`

The repo is private because it's a client's system. Screenshots and a demo are on [my portfolio](https://ghulam-mustafa-ms.vercel.app).

### Kartak · food-safety exam practice app
*Client: a Saudi restaurant · Oct 2026 to present · in live use*

A phone app that prepares food workers in Saudi Arabia for their health certificate exam, paid for by a Saudi restaurant for its staff.

- Works in 11 languages, including right-to-left Arabic and Urdu, and offline after the first visit
- Separate seller app that issues one-phone access codes and shows who is ready for the exam
- Parameterised SQL, hashed admin password, secrets kept out of the code
- 154 automated checks, including phone-sized browser tests in every language

`JavaScript` `Node.js serverless` `PostgreSQL (Neon)` `Vercel` `Playwright`

### Final-year project · Predicting and Preventing Perishable Food Waste in Hospitality with Machine Learning
*In partnership with industry partner growyze · due June 2027*

A system that predicts which perishable stock in a hospitality business is likely to go to waste and suggests what to order and promote.

### [Local AI Gmail Sorter](https://github.com/GhulamMustafa-MS/local-gmail-ai-sorter)
A Python tool I built and use myself. It sorts Gmail with rules first and a local model through Ollama as a fallback, so my email never leaves my laptop.

`Python` `Gmail API` `SQLite` `Ollama`

### Earlier work
- [Car Service Database](https://github.com/GhulamMustafa-MS/car-service-database-system): normalised MySQL schema, ER diagram and reporting queries
- [Work Hours Tracker](https://github.com/GhulamMustafa-MS/java-work-hours-tracker): Java console program with file I/O

---

## Skills

| | |
|---|---|
| **Languages** | Python, SQL, JavaScript, Java (basics) |
| **Backend & data** | FastAPI, SQLAlchemy, REST APIs, PostgreSQL, SQLite, MySQL, serverless functions |
| **Testing & delivery** | pytest, Playwright, GitHub Actions, Git, Vercel, Neon |
| **Cloud** | AWS (studying for Solutions Architect Associate), Azure (coursework) |
| **AI tools** | Claude Code and other AI coding assistants, Ollama (local LLMs) |

## Education

**BSc (Hons) Computing Systems**, Ulster University London · 2024 to 2027
Year 1: 79% (Dean's List) · Year 2: 77% · BCS student member

Alongside my degree I'm Head of Kitchen Training at Another Brother Cafe in London, so I know what happens when software meets a busy shift.

Available full-time from June 2027.
