# Abhishek Singh

**IT Specialist Officer at State Bank of India, Bengaluru** · 7+ years in backend development

[![Website](https://img.shields.io/badge/website-abhi1kush.github.io-blue)](https://abhi1kush.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek--singh-0A66C2?logo=linkedin)](https://www.linkedin.com/in/abhishek-singh-6658493b)
[![GitHub](https://img.shields.io/badge/GitHub-abhi1kush-181717?logo=github)](https://github.com/abhi1kush)
[![Email](https://img.shields.io/badge/email-abhi1kush%40gmail.com-red)](mailto:abhi1kush@gmail.com)

- 🌐 Live site: <https://abhi1kush.github.io>
- 📄 CV: <https://abhi1kush.github.io/cv/>
- 💼 LinkedIn: [www.linkedin.com/in/abhishek-singh-6658493b](https://www.linkedin.com/in/abhishek-singh-6658493b)
- 🐙 GitHub: [abhi1kush](https://github.com/abhi1kush)

## Summary

IT Specialist Officer at State Bank of India (since July 2025), with 7+ years of experience in backend development, previously at MakeMyTrip, Druva, Embibe, and Huawei. M.Tech in Computer Science and Engineering from IIT Bombay.

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Go (Golang), Rust, C++, Python, Bash, TypeScript |
| Backend & APIs | REST APIs, API contracts, microservices (OCR), Kafka |
| Cloud & Data | AWS S3, DynamoDB |
| Testing & CI | Integration / E2E / component test frameworks, Jenkins (Groovy), GitHub Actions, Scapy |
| Systems | Distributed NAS storage & caching, IoT network stacks (lwIP, uIP, RPL) |
| Frontend | React, Vite, WebAssembly |

## Experience

### IT Specialist Officer — State Bank of India, Bengaluru
*July 2025 – Present*

### Senior Software Engineer 2 (Golang) — MakeMyTrip, Bengaluru
*Sept 2022 – April 2024*
- Product requirement collection and analysis; implementation of product features in Golang.
- Prepared API contracts between downstream API providers and API-consumer UI clients.
- Config management; production issue root-cause analysis and fixes.
- Developed an integration-level test automation framework using Golang, Bash, Kafka and Jenkins-Groovy.
- Implemented pixel-data logging of user activity on the website for Data Science consumption.

### Staff Software Engineer (Golang) — Druva Inc, Pune
*From Sept 2020*
- Implemented Golang REST APIs for backing up user data using AWS S3 and DynamoDB.
- Designed and implemented a framework for E2E and component testing of REST APIs.

### Software Development Engineer 1 — Embibe (EdTech), Bengaluru
*From Nov 2019*
- Designed and implemented an OCR web micro-service for recognising handwriting and text in images, with automated image preprocessing.
- Contributed to REST APIs converting exam questions in doc format to JSON objects in the database.
- Worked on redesigning and implementing automated test question-paper generation.

### Technical Project Leader — Huawei Technologies India Pvt. Ltd, Bengaluru
*From July 2017*
- **Distributed Network Attached Storage (NAS):** optimisations for large IO operations on a distributed file system; protocol for managing a distributed cache; distributed Read-Ahead Cache management.
- **IoT network stacks (lwIP, uIP):** Linux support for RPL; RFC implementations and IOCTLs for lwIP; bug fixes in open-source code; unit and functional testing with Python and Scapy (Castellia framework).
- Designed and implemented an MP4 video preview maker in C++ from scratch.

## Education

| Degree | Institute | University / Board | Year |
| --- | --- | --- | --- |
| M.Tech, Computer Science & Engg. | IIT Bombay | IIT Bombay | 2017 |
| B.Tech, Computer Science & Engg. | MMMEC Gorakhpur | G.B.T.U. | 2013 |
| Intermediate | SSMV | CBSE | 2009 |
| Matriculation | JNV Shahjahanpur | CBSE | 2007 |

**Academic project:** Authentication using finger movement on an Android phone touch screen (Machine Learning).

## Projects

| Project | Description | Live | Repo |
| --- | --- | --- | --- |
| Chess Analysis Tool | Chess.com-style game review: upload a PGN and step through the game with in-browser engine analysis. | [Open](https://abhi1kush.github.io/chess-frontend/) | [chess-frontend](https://github.com/abhi1kush/chess-frontend) |
| Maven Offline Bundler | Paste a pom.xml (or upload a screenshot / QR codes) and get a zip of every Maven dependency and plugin, resolved by GitHub Actions, for offline builds. | [Open](https://abhi1kush.github.io/maven-offline-bundler/) | [maven-offline-bundler](https://github.com/abhi1kush/maven-offline-bundler) |
| Fibonacci Clock | React Fibonacci clock: five squares worth 1, 1, 2, 3, 5 show the time in colours, with a fresh random face every minute. | [Open](https://abhi1kush.github.io/fibonacci-clock/) | [fibonacci-clock](https://github.com/abhi1kush/fibonacci-clock) |
| 2048 | The classic 2048 puzzle in React + TypeScript with keyboard and swipe controls, animations and a saved best score. | [Open](https://abhi1kush.github.io/2048/) | [2048](https://github.com/abhi1kush/2048) |
| Stock Delivery Trading Simulator App | The trading engine compiled to WebAssembly in a React + Vite + TypeScript app: edit a policy, run backtests in the browser, view KPIs and charts. | [Open](https://abhi1kush.github.io/stock-delivery-trading-simulator-app/) | [stock-delivery-trading-simulator-app](https://github.com/abhi1kush/stock-delivery-trading-simulator-app) |
| Stock Delivery Trading Simulator | Rust backtesting engine for long-only delivery trading with YAML-defined technical policies (EMA/ADX/RSI, ATR stops, SMA100 trend filter), strict no-look-ahead causality, P&L reports and charts. | — | [stock-delivery-trading-simulator](https://github.com/abhi1kush/stock-delivery-trading-simulator) |

## Running this site locally

This is a [Jekyll](https://jekyllrb.com/) site. With Docker:

```bash
docker compose up        # serves on http://localhost:8080
```

Or with Ruby/Bundler:

```bash
bundle install
bundle exec jekyll serve --lsi   # http://localhost:4000
```

See [INSTALL.md](INSTALL.md) and [CUSTOMIZE.md](CUSTOMIZE.md) for details.

---

Built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT license).
