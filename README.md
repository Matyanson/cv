# Matyáš Peremský

**Software Developer**

Hradec Králové, Czech Republic
+420 605 551 818 · [matyas.perem@seznam.cz](mailto:matyas.perem@seznam.cz)
LinkedIn: linkedin.com/in/matyas-peremsky
GitHub: github.com/Matyanson
Stack Overflow: stackoverflow.com/users/12518099/matyanson

Born 2001 · Driving licence B

---

# Profile

Software developer and Applied Informatics student with strong experience in web development, particularly TypeScript/JavaScript and modern web frameworks. Comfortable with Java and Spring Boot as well as Python, databases, APIs and software architecture.

Experienced in developing complete applications independently, from requirements and design through implementation and deployment. Interested in algorithms, GPU programming, image processing, graphics, embedded systems and software architecture.

Started learning JavaScript in 2018 and have since developed numerous personal, academic and professional projects.

---

# Skills

## Programming Languages

* **TypeScript / JavaScript** — very comfortable
* **Java** — comfortable
* **Python** — comfortable
* **C#** — basic
* **C++** — basic, currently developing further
* **GLSL / OpenGL** — 1–2 years of experience

## Web Development

* SvelteKit
* React.js / Next.js
* Vue.js
* Thymeleaf
* Spring Boot
* Spring MVC
* Spring Security
* REST APIs
* WebSockets
* Server-side rendering
* WebGL

## Databases / Data

* SQL
* PostgreSQL
* NoSQL
* MongoDB
* Redis
* Firebase
* Firestore
* Hibernate
* Spring Data JPA
* Prisma
* ORM

## Tools / Platforms

* Git / GitHub
* Docker
* Vercel
* Linux
* Windows / PowerShell
* ESP32
* RTOS
* Arduino
* Raspberry Pi

---

# Education

## University of Hradec Králové

### Master's Degree — Applied Informatics

**2024 – present**

Currently enrolled in the Master's programme in Applied Informatics. Expected graduation: 2027.

Master's thesis topic has not yet been finalized. A possible topic is the development of the Fible 3D-printing application.

### Bachelor's Degree — Applied Informatics

**2021 – 2024**

Bachelor's thesis:

**Webová aplikace pro hledání cest na herní mapě**

Grade: **A**

Developed a web application for finding paths through Trackmania game maps. The problem is a specialized graph-search problem where a vehicle must start at a starting point, pass all required checkpoints and ring checkpoints, and reach the finish. Unlike the standard travelling salesman problem, a vehicle can teleport back to a previously passed non-ring checkpoint when forming a route.

Designed and implemented a custom "reverse search" algorithm and compared it against a brute-force approach. The custom algorithm achieved a very large performance improvement over brute force.

Technologies:

* SvelteKit
* Web Workers
* Vercel

Live application:
https://tm-cutfinder.vercel.app/

---

# Study Abroad

## National Dong Hwa University — Taiwan

**Spring semester 2026**

Courses:

### Large Language Models and Applications

* CrewAI
* OpenEvolve
* AgentSociety Challenge

### Intelligent IoT Technologies and Applications

* ESP32
* Tinkercad
* Hardware
* C++

### Image Processing

* Histogram normalization
* Fourier transform
* Image classification
* PyTorch

### Fundamental Chinese

---

## Kochi University of Technology — Japan

**Spring semester 2023**

Courses:

* Web Media

  * Reports on web standards
* Basic Japanese
* Speech Communication
* Presentation
* Academic Presentation

---

# Professional Experience

## Freelance Software / Web Developer — OSVČ

**2022 – present**

Independent development of software and web tools for clients.

### Custom website — 2022

Designed and developed a website for a private client independently, including communication with the client, design, implementation, hosting and deployment.

* Designed the website in Figma
* Implemented the website in WordPress
* Used and customized a WordPress template
* Designed individual page blocks using Elementor and custom styling
* Added plugins for SEO, GDPR and cookie management
* Used custom CSS where necessary
* Set up domain and hosting
* Deployed the website to WEDOS
* Currently live at https://avonsvetkrasy.cz/

### Tools for kindergartens — 2025–2026

Developed tools and assisted directors of approximately 4–5 kindergartens.

* Created interactive Excel forms with connected dropdown menus and filtering
* Helped directors use LLM-based tools
* Used LLMs to assist with generating reports
* Helped with document formatting and Word document styling
* Communicated directly with clients and adapted tools to their needs

---

# Internships

## BMAS Agency Ltd.

**September – October 2019**

Developed a multipage web form as part of an existing web project.

* React.js
* Gatsby.js
* Designed and implemented custom CSS styles and reusable components

---

## S.I.C. Ltd.

**May 2019**

Worked with Linux servers and virtual machines.

* Linux server installation
* SSH / PuTTY
* FTP
* SQL installation
* Server virtual machines

---

## Softgate Ltd.

**May – June 2018**

Worked on an existing internal PowerShell TUI tool for preparing clean Windows installations.

Implemented functionality for configuring Windows machines, including:

* Windows configuration
* Registry modifications
* Installing programs
* Uninstalling programs

---

# Personal and Academic Projects

## Fible

**Svelte.js · WebGL · Compute Shaders**

An application for generating 3D-printable images using a limited palette of filament colors. The goal is to reproduce an image using only a small number of available filament colors, similar to HueForge.

The application processes all pixels of the original image and uses a custom algorithm to find a visually similar result with the limited filament palette. GPU acceleration through compute shaders is used to make the large-scale pixel processing practical.

* Researched, designed and implemented the project independently
* Developed the color-processing algorithm
* Implemented GPU acceleration using compute shaders
* Physically validated the algorithm by producing a 3D-printed prototype that visibly reproduced the original image
* Currently under active development
* Not yet publicly deployed

Potential master's thesis topic.

---

## Daki.moe

**SvelteKit · SSR · Web Scraping · Query Parser · TypeScript**

A dakimakura search engine that searches and aggregates products from external websites.

The application implements a custom full-text query language supporting structured expressions such as:

`character:(name:megumin eye-color:(blue or red)) usd<=50`

* Designed and implemented the query language and its grammar
* Implemented the full-text query parser
* Developed the web scraper independently
* Searches external websites and scrapes results on demand
* No local product database is required
* SvelteKit backend with server-side rendering
* Deployed on Vercel
* Designed so additional source websites can be added
* Developed independently over several months
* Currently operational

https://www.daki.moe/

---

## Trading Bot

**Python · Svelte.js · WebSockets · Alpaca API**

A working trading application consisting of a trading server and client for designing, running and visualizing automated trading strategies.

The current architecture consists of several specialized managers:

* MainManager / application context
* StrategyManager
* OrderManager
* BudgetManager for budget and P&L
* ApiManager for communication with the client

The application uses an event-driven architecture with events such as:

* `on_quote` for price updates
* `on_trade` for budget and P&L updates

The architecture allows new strategies and order types to be implemented without having to repeatedly implement common event handling and property updates.

* Working end-to-end application
* Currently integrated with the Alpaca broker API
* WebSocket communication between server and client
* Designed with future broker abstraction in mind

https://github.com/Matyanson/trade-offer

---

## Parallax.css

**CSS · npm**

An npm library for creating scrolling parallax effects using CSS only, without JavaScript.

The library uses mathematical transformations to position and scale elements according to their virtual distance, creating a parallax effect.

* Designed and implemented independently
* Published as an official npm package
* No JavaScript required for the effect
* Includes dedicated documentation and interactive examples
* Approximately 1,000 npm downloads
* Continues to receive weekly downloads
* 4 GitHub stars

Documentation:
https://matyanson.github.io/parallax.css/

---

## Minecraft Shader / Boxeh Shader

**OpenGL · GLSL**

A complete Minecraft shader pack developed independently over more than a year.

The project focuses on both performance and visually realistic effects based on real-world physical constants.

Implemented effects include:

* Screen-space reflections

* Refraction

* Light absorption

* God rays

* Atmospheric fog

* Other screen-space and lighting effects

* Entire shader pack written independently

* Focused heavily on performance optimization

* Publicly downloadable

* GitHub is the main project repository

https://github.com/Matyanson/boxeh-shader

---

## Smart Chess Board

**ESP32 · C++ · RTOS · Hall-effect sensors · Servos**

An ongoing project to build a physical chess board that can play against online opponents through Lichess.

The planned board will detect chess pieces and physically move them using an automated XY mechanism.

Current development focuses on the embedded firmware:

* ESP32 firmware
* Piece detection using Hall-effect sensors
* Hall-effect sensor matrix
* Rack-and-pinion XY movement system using servos
* Lichess API integration planned as part of the complete system
* Hardware and firmware developed independently

Current stage: piece-detection firmware and board hardware development.

https://github.com/Matyanson/chess-move-detection-prototype

---

## Earth Map Projections

**Svelte.js · WebGL · GLSL**

An interactive application for visualizing different mathematical world-map projections.

Users can experiment with projection formulas and visualize how geographic coordinates are transformed into map coordinates.

* Approximately 10 implemented projections
* Projection formulas based on published mathematical formulas
* Reimplemented the formulas in GLSL
* Designed so additional projections can be added easily
* Future goal: allow users to define their own projection formulas

Live application:
https://world-map-projections.vercel.app/

---

## Anime Tracking Application

**Java · Spring Boot · Spring MVC · Thymeleaf · Spring Security · PostgreSQL · Hibernate · Spring Data JPA**

A school project for tracking anime, similar to MyAnimeList.

Implemented as a Spring Boot MVC application with:

* User registration and authentication
* Spring Security
* Custom user watchlists
* Rating system
* PostgreSQL database
* Hibernate
* Spring Data JPA / ORM
* Thymeleaf frontend
* Maven / Gradle

The project was developed as a university/school project. The UI is simple and primarily demonstrates the backend and application architecture.

---

## DIY Video Platform — DIWhy

**React.js · Next.js · Firebase Firestore · Firebase Storage · Vercel**

High-school graduation project developed between June 2020 and May 2021.

A web application for DIY video tutorials. Users can search for videos and filter them using parameters such as:

* Name
* Materials
* Tools
* Tags
* Category

Each video contains interactive step-by-step instructions synchronized with the video timeline.

Developed the application independently.

---

# Self-Education

Started learning JavaScript in 2018 and have continuously developed personal projects while learning additional frameworks, technologies and programming concepts.

Areas explored include:

* Web development
* Software architecture
* Algorithms
* Graphics programming
* Machine learning
* Embedded development
* Databases
* APIs

GitHub:
https://github.com/Matyanson

Stack Overflow:
https://stackoverflow.com/users/12518099/matyanson

---

# Certificates

* Cisco Certified Network Associate — Routing and Switching
* CCNA Routing and Switching: Introduction to Networks — 2021
* Cisco Cybersecurity Essentials — 2025
* Cisco Networking Essentials — 2018
* Oracle Database Foundations — 2018
* Oracle Database Design and Programming with SQL — 2019
* ECDL Profile Certificate — 2021
* Microsoft Office Specialist — 2018
* CTU Introduction to Computer Science — 2019
* BMAS London Work Experience Certificate — 2019
* Google Digital Garage — Fundamentals of Digital Marketing — 2019
* Google Analytics for Beginners — 2019 (expired)

---

# Languages

* **Czech** — native
* **English** — C1
* **Japanese** — fundamental
* **Chinese** — fundamental

---

# Hobbies and Interests

* Hiking
* Cycling
* Skiing
* Squash
* Football
* Calisthenics
* FPV drones
* Video editing
* Arduino and Raspberry Pi
* Magic: The Gathering
* Trackmania
* Rubik's Cube
