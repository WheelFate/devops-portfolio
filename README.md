# My DevOps Portfolio

Welcome to the central hub of my DevOps journey and practical projects! This repository showcases my hands-on experience with various DevOps principles, tools, and methodologies, demonstrating how I approach software delivery, infrastructure automation, and operational excellence.

---

## About Me & My DevOps Philosophy

Hi! I'm passionate about building robust, scalable, and efficient software delivery pipelines. My philosophy revolves around **automation**, **collaboration**, and **continuous improvement**. I believe in leveraging modern tools and practices to reduce manual effort, accelerate development cycles, ensure high availability, and foster a culture of shared responsibility between development and operations.

This portfolio is a testament to my commitment to continuous learning and applying DevOps concepts to real-world scenarios.

---

## Projects Overview

Here's a curated list of my DevOps projects. Each entry provides a brief description, highlights key concepts, and links directly to its dedicated GitHub repository for a deeper dive.

### 1. [Simple Log Aggregator](https://github.com/WheelFate/simple-log-aggregator)
* **Description:** A basic, no-installation demonstration of a file-based log aggregation system with a simple web interface for searching. It leverages GitHub for storage and GitHub Pages for hosting, ideal for beginners.
* **Key Concepts:** Log Management, Observability, Basic Web Interface, GitHub Pages, `guide.md` documentation.
* **Technologies:** HTML, CSS (Tailwind), JavaScript, GitHub Pages.

### 2. [Zero-Downtime Online Demo](https://github.com/WheelFate/zero-downtime-online-demo)
* **Description:** This project provides a hands-on, no-installation simulation of Zero-Downtime Deployment (ZDD) concepts. It uses a simple Flask application, Docker for packaging, and GitHub Actions to automate and demonstrate the core ZDD steps, including health checks and traffic shifting.
* **Key Concepts:** Zero-Downtime Deployment (ZDD), High Availability, Deployment Strategies, Continuous Delivery, Docker, GitHub Actions, Health Checks, Traffic Shifting.
* **Technologies:** Python (Flask), Docker, GitHub Actions, `curl`.

### 3. [Simple IP Service Discovery](https://github.com/WheelFate/simple-ip-service-discovery)
* **Description:** This project demonstrates the fundamental concepts of **Service Discovery** using entirely static files hosted on GitHub Pages. It simulates a basic service registry where "services" (simple HTML pages) register their information (like IP, port, description, and status) in a central JSON file. A "client" application (the main `index.html` page) then queries this registry to "discover" and display available services, all without any installations.
* **Key Concepts:** Service Discovery, Microservices Principles, Client-Side Discovery, Static Registry, Health Status Simulation, JSON Data Handling.
* **Technologies:** HTML, CSS, JavaScript, JSON, GitHub Pages.

### 4. [Canary Deployment Demo](https://github.com/WheelFate/canary-deployment-demo)
* **Description:** This project demonstrates a simplified "canary deployment" strategy for a static website, utilizing GitHub Pages. It illustrates the core concept of rolling out a new version to a subset (simulated by switching the deployed branch on GitHub Pages) and provides methods to "promote" or "rollback" manually, all without any local software installations and completely free.
* **Key Concepts:** Canary Deployment, Risk Reduction, Gradual Rollout, Static Site Deployment, GitHub Pages, Branching Strategies, Manual Promotion/Rollback.
* **Technologies:** HTML, CSS, GitHub Pages, GitHub Branches.

### 5. [Rainbow Deployment Beginner](https://github.com/WheelFate/rainbow-deployment-beginner)
* **Description:** This project offers a **beginner-friendly, 100% online guide** to **Rainbow Deployment** (often synonymous with Blue/Green). It visually demonstrates how to deploy multiple application versions, split traffic safely, and test/rollback changes using free, web-based tools like GitHub, Replit, and Render, with no local installations required.
* **Key Concepts:** Rainbow/Blue-Green Deployment, Traffic Splitting, Versioning, Rollback Strategy, Online-Only Setup, Static Web Hosting.
* **Technologies:** GitHub, Replit, Render (optional), HTML, CSS, JavaScript, Mermaid.js.

### 6. [Acceptance Testing Tutorial](https://github.com/WheelFate/acceptance-testing-tutorial)
* **Description:** This project serves as a simple example and tutorial to understand and implement **Acceptance Testing**. It demonstrates how web-based applications can be tested to ensure they meet user requirements and business specifications.
* **Key Concepts:** Acceptance Testing, Software Quality Assurance, Test Automation Basics, User Requirements Verification.
* **Technologies:** JavaScript, HTML.

### 7. [Hello Continuous Deployment](https://github.com/WheelFate/hello-continuous-deployment)
* **Description:** This is a simple, beginner-friendly project designed to demonstrate the concept of **Continuous Deployment (CD)** using GitHub Actions and GitHub Pages. It showcases an automated pipeline where every merge to the `main` branch triggers an automatically timestamped build and deployment to a live URL, illustrating CD without any manual intervention.
* **Key Concepts:** Continuous Deployment (CD), Automation, GitHub Actions, GitHub Pages, Automated Builds, Release Pipelines, Source Control Integration.
* **Technologies:** HTML, GitHub Actions, GitHub Pages.

### 8. [Rolling Deployment Demo](https://github.com/WheelFate/rolling-deployment-demo)
* **Description:** This guide demonstrates a "Blue-Green" rolling deployment strategy using GitHub and Vercel for a static website. It illustrates how to release new versions with zero downtime and provides an instant rollback option by managing two distinct environments ("Blue" for current, "Green" for new) and switching live traffic between them.
* **Key Concepts:** Blue-Green Deployment, Rolling Deployment, Zero Downtime, Instant Rollback, Traffic Switching, Static Site Deployment.
* **Technologies:** HTML, GitHub, Vercel.

### 9. [Ephemeral Demo](https://github.com/WheelFate/ephemeral-demo)
* **Description:** This project guides users through setting up **Ephemeral (Preview) Environments** for web projects using GitHub and Vercel. It demonstrates how every Pull Request automatically triggers the creation of a temporary, live version of the site, enabling easy review and testing before merging to production, all using free and online tools.
* **Key Concepts:** Ephemeral Environments, Preview Environments, Pull Request Automation, Continuous Integration/Delivery, Branching Strategies, Automated Testing (via preview).
* **Technologies:** HTML, GitHub, Vercel.

### 10. [CI Demo](https://github.com/WheelFate/ci-demo)
* **Description:** This project provides a clear, simple example of **Continuous Integration (CI)** using a Python application with GitHub Actions. It demonstrates how automated builds and tests (`test_main.py`) are triggered upon code changes, ensuring code quality and rapid feedback in the development cycle.
* **Key Concepts:** Continuous Integration (CI), Automated Builds, Automated Testing, Code Quality, GitHub Actions, Unit Testing.
* **Technologies:** Python, GitHub Actions.

---

## Why This Portfolio?

This collection of projects is designed to:
* **Showcase my practical skills** in implementing various DevOps practices.
* **Demonstrate my understanding** of the full software development lifecycle.
* **Highlight my problem-solving approach** to common challenges in software delivery and operations.
* **Provide tangible examples** of my work in automation, deployment, and infrastructure.

---

## Get in Touch

You can find me on GitHub:

* **GitHub:** [https://github.com/WheelFate](https://github.com/WheelFate)

---

### Pro-Tip for Your Individual Project Repos:

For maximum impact, consider adding the following to the `README.md` of *each individual project*:
* **Screenshots or GIFs:** Visuals of the application or pipeline in action are incredibly powerful.
* **"How to Run" Instructions:** Make it easy for others to clone and test your projects.
* **Detailed Architecture/Flow:** A simple diagram explaining how the components interact.
