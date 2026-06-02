
# Iván Ramírez (irf87) — Tech Lead & Front-End Engineer
Solving performance bottlenecks and structural complexity at the intersection of business logic and UI architecture.

## 🛠️ Technical Core
* **Architecture:** Clean Architecture, Domain-Driven Design (DDD), Hexagonal Design.
* **Frontend:** React, Next.js, TypeScript, SSR/CSR Optimization.
* **Optimization:** DOM Virtualization, Profiling, Memory Management, Bundle Optimization.
* **Leadership:** Tech Lead,  TDD/BDD, Spec-Driven Development.

---

## 🚀 Impact-Driven Projects

### 📦 [prices-scraper](https://github.com/irf87/prices-scraper) — Sequential Price Monitoring
Personal-scale price tracking system designed for embedded hardware (Raspberry Pi/Orange Pi) with a focus on memory-constrained execution.
* **Architecture:** Sequential execution model. A single Chromium instance per process ensures bounded peak memory usage, prioritizing system stability over raw concurrency.
* **Anti-Detection:** Fingerprint spoofing (navigator.webdriver override, locale/geo-spoofing) to ensure functional continuity in personal deployments.
* **Stack:** Node.js, Playwright, SQLite, Docker.

### 📱 [price-scraper-app](https://github.com/irf87/price-scraper-app) — Mobile Tracking Client
Cross-platform interface for `prices-scraper` with a focus on offline-first UX.
* **State Management:** Zustand + React Query (TanStack Query) for efficient API synchronization.
* **DevOps:** Fully automated CI/CD pipeline via GitHub Actions, triggering Android APK distribution upon version tagging.
* **Stack:** React Native, TypeScript, React Hook Form, MMKV.

### 🩺 [DATEMApp](https://datem.app/en/) — Local-First Health Platform
Zero-backend clinical health management application.
* **Distributed State Architecture:** Implements a client-side transaction ledger using an *append-only JSON* model.
* **Synchronization:** Employs Optimistic Concurrency Control (OCC) matched with native cloud revision tracking to handle distributed race conditions.
* **Conflict Resolution:** Last-Write-Wins (LWW) engine with ID-mapping safeguards for offline record creation.
* **Compaction:** Automated transaction-log squashing to prevent metadata bloat, ensuring high-performance read cycles on low-end mobile devices.

---

## 📈 Strategic Engineering Contribution (Recent Highlights)

* **Architectural Clean-up (Eden Medical):** Implemented Clean Architecture using Strategy and Factory patterns to decouple event-logging visual logic from domain entities. This enabled parallel feature development and 0-regression deployments.
* **Performance Profiling (Eden Medical):** Resolved PACS (DICOM) dashboard latency by migrating to modern virtualized table engines, verified through browser GPU/JS profiling traces to ensure thread stability under high data density.
* **Process Standardization:** Authored and institutionalized technical specification workflows (SPECs) and *Definition of Ready* (DOR) protocols, resulting in a 90% accuracy rate in sprint estimations and a significant reduction in production hotfixes by aligning Product and Tech expectations prior to development.

---

## 📫 Connect
- [LinkedIn](https://www.linkedin.com/in/irf87/)
