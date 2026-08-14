# Hi, I'm Hristijan Chupetreski 👋

### Software Engineer · Full-Stack Development · Cloud & DevOps

I'm finishing my **Bachelor's degree in Computer Science** at **FAMNIT, University of Primorska**, Slovenia.

I build **full-stack applications, distributed systems, desktop software and applied AI prototypes**, with a strong focus on how complete systems are designed, connected, deployed and maintained.

My main stack revolves around **C# / .NET, Angular, React, Java, Node.js, PostgreSQL and Docker**, with additional experience in **Python, AWS, Azure, Linux infrastructure, computer vision and scientific computing**.

Beyond coursework, I've worked on **business software, real client platforms, cloud-based systems, distributed networking, computer vision prototypes and EEG research**.

Currently expanding further into **software architecture, machine vision, Edge AI and production-oriented backend systems**.

---

# 🛠️ Tech Stack

### Languages

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge\&logo=csharp\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge)

### Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge\&logo=angular\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)

Component architecture · routing · responsive interfaces · API integration · real-time UI · state-driven interfaces

### Backend & Application Development

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge\&logo=springboot\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge\&logo=django\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)

**ASP.NET Core · REST APIs · Entity Framework Core · Express · FastAPI · WPF · MVVM · WebSockets · JWT · layered architectures**

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge\&logo=amazondynamodb\&logoColor=white)

Relational modeling · schema design · normalization · migrations · persistent application state · query design

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonwebservices\&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge\&logo=cloudflare\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

Docker Compose · multi-container systems · container networking · Linux VPS · reverse proxies · DNS/CDN · environment configuration · CI/CD concepts · cloud deployment

---

# 🚀 Selected Projects

## 🩺 ICOF Congress Platform

Full-stack platform being developed for an **international medical congress**, designed as a long-term public website and event-management system rather than a static event page.

**Angular · ASP.NET Core · PostgreSQL · Entity Framework Core · Docker · Azure**

The system is designed around:

* user accounts and authentication
* congress and programme management
* workshops, lectures and timetable content
* event registration
* participants, speakers and ambassadors
* role-based administration
* editable public content
* media management
* scalable backend infrastructure

The deployment architecture is designed around **containerized services, managed PostgreSQL, cloud-hosted media and CDN/DNS infrastructure**, with capacity and load testing considered as part of the system design.

---

## 🎱 GalaxyClub — Reservation Platform

Full-stack reservation system built for a **billiard club / coffee house**.

**Angular · ASP.NET Core · PostgreSQL · Docker · Nginx**

The platform implements a real reservation model rather than simple form submission.

Reservation logic includes:

* configurable operating hours
* 30-minute reservation slots
* booking duration limits
* advance reservation windows
* table availability validation
* automatic table allocation
* backend-driven reservation processing

The public repository contains the frontend showcase while the full backend and production configuration remain private.

---

## 🧾 MCS MyTravel — Travel Agency Management System

Desktop business application built to automate workflows for a **travel agency**.

**C# · .NET 8 · WPF · MVVM · Entity Framework Core · PostgreSQL**

The application models a complete business workflow around:

**Client → Booking → Passengers → Documents → Payments**

Core functionality includes:

* client and contact management
* booking management
* multiple passengers per booking
* travel information and booking details
* installment and payment tracking
* vouchers
* agreements
* invoices
* reusable document models
* structured desktop UI state management

The application uses a centralized PostgreSQL database so business data can be accessed consistently across multiple workstations.

---

## 🧅 Onion Routing / Mix Network

Java-based distributed networking prototype demonstrating **multi-hop onion routing**.

**Java · Maven · Docker · HTTP · Cryptography**

The current implementation runs a Dockerized network of independent mix nodes:

`Client → Node 1 → Node 2 → Node 3 → Destination`

Each node decrypts only its own onion layer and learns only enough information to forward the packet to the next hop.

The system implements:

* layered onion packet construction
* **AES-GCM** payload encryption
* **RSA-OAEP** key wrapping
* HTTP transport between nodes
* JSON/Base64 packet serialization
* Dockerized mix nodes
* exit-node HTTP requests
* encrypted response routing
* forward and reply onion paths
* unit and end-to-end testing

The project is intentionally an educational anonymity-network prototype rather than a production privacy system.

---

## 🧠 Remember Me — Computer Vision Hackathon Prototype

Smart-glasses-inspired memory assistance prototype built during **Dragonhack 2026**.

**React · Node.js · Express · Python · FastAPI · FaceNet · DeepFace · PostgreSQL · Docker**

Built as a multi-service architecture:

`Camera → React → Express API → ML Service → PostgreSQL`

The frontend performs live face detection and sends detected face regions to a Python ML service.

The system includes:

* browser-based camera capture
* TinyFaceDetector / face-api.js
* face cropping and throttled image processing
* FastAPI ML microservice
* FaceNet embeddings
* 128-dimensional face representations
* PostgreSQL profile and interaction storage
* Dockerized database infrastructure
* AR-style contextual overlays

Built from idea to working end-to-end prototype during a **24-hour hackathon**.

---

## 🧠 Bachelor's Thesis — EEG Functional Connectivity

### Brain Functional Connectivity Analysis via Multivariate Regression of Electroencephalographic Signals

Research project focused on extracting and evaluating **functional brain connectivity from EEG recordings**.

**MATLAB · Signal Processing · Autoregressive Modeling · Statistical Analysis · Machine Learning**

The work uses EEG data from the **PhysioNet EEG Motor Movement/Imagery Dataset** and compares brain connectivity representations between experimental conditions.

Pipeline includes:

* EEG preprocessing
* filtering and resampling
* ICA-based artifact processing
* windowed signal analysis
* bivariate connectivity estimation
* multivariate autoregressive modeling
* connectivity feature extraction
* statistical comparison
* SVM classification
* cross-validation

The research investigates how multivariate modeling changes the representation of connectivity compared with simpler pairwise approaches.

---

## 🔄 Student Trade

Distributed information system designed for **student-to-student buying, selling and trading**.

**React · Node.js · PostgreSQL · AWS S3 · WebSockets · JWT · Aiven**

The project combines:

* user authentication
* marketplace listings
* relational application data
* image/file storage
* real-time messaging
* WebSocket communication
* cloud-hosted database infrastructure

The idea was designed around a practical problem: providing students with a dedicated platform for exchanging items without relying entirely on generic marketplaces and social-media groups.

---

## 🏠 HomeFind — Angular + .NET Full-Stack Application

Full-stack real-estate application developed around the **Angular + ASP.NET Core ecosystem**.

**Angular · C# · ASP.NET Core · Entity Framework Core · SQL Server · Docker · Nginx**

Built around a standard client-server architecture:

`Angular → REST API → Database`

with deployment architecture extending to:

`Angular → Nginx → ASP.NET Core API → Database`

The project covers:

* RESTful API design
* CRUD workflows
* frontend/backend separation
* Entity Framework data access
* backend validation
* centralized error handling
* environment-based configuration
* CORS
* containerization
* multi-service deployment architecture

---

## ☁️ Prime Tech Repairs

Cloud-oriented service-management application.

**Django · React · Node.js · AWS**

Worked with AWS services including:

* DynamoDB
* Lambda
* Step Functions

The project explored serverless and event-driven approaches for application workflows and cloud data management.

---

# 🔬 Engineering Interests

My current focus is moving beyond simply building applications toward understanding the **systems underneath them**:

* Software Architecture
* Backend Engineering
* Distributed Systems
* Cloud & DevOps
* Machine Vision
* Edge AI
* Computer Vision
* Applied Machine Learning
* Production Deployment

I enjoy projects where **software, infrastructure and real-world constraints meet**.

---

# 📊 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=cupetre\&show_icons=true\&theme=radical)

![GitHub Streak](https://streak-stats.demolab.com?user=cupetre\&theme=radical\&hide_border=false)

---

# 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/hristijan-chupetreski-70001a29b/)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:cupetre_kiko@yahoo.com)

---

### `Build → Break → Understand → Improve`
