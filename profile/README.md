# dblayer.dev

This organization contains all the repositories required to build, run, and extend **dblayer.dev**.

## What is DBlayer?

**DBlayer** is a platform that helps you create APIs and internal apps directly on top of your database, **without building or maintaining a traditional backend**.

It removes the complexity of backend development by acting as a secure middleware between your application and your database, allowing you to focus on product logic instead of infrastructure.

---

## What is an API?

APIs are the primary way applications interact with databases. Traditionally, creating APIs requires:

* Designing backend services
* Managing servers and deployments
* Handling authentication, security, and scaling

DBlayer eliminates this overhead.

With DBlayer:

* You connect your database directly
* Write custom SQL queries
* Instantly expose them as managed APIs

DBlayer handles execution, security, and lifecycle management, so you don’t need to worry about backend maintenance.

---

## What are Apps in DBlayer?

Many use cases require simple internal tools such as:

* Tables
* Charts
* Forms
* Dashboards

DBlayer Apps allow you to build these interfaces directly on top of your database and APIs without writing a separate frontend or backend application.

You can:

* Create custom tables, charts, and inputs
* Apply business logic
* Use them as internal tools or admin panels

All without additional infrastructure.

---

## Repositories

Below is an overview of the repositories in the **dblayer.dev** organization:

### 1. Dashboard

**Repository:** [https://github.com/dblayer-dev/dashboard.dblayer.dev](https://github.com/dblayer-dev/dashboard.dblayer.dev)

Contains the main dashboard UI/UX where users can:

* Add and manage databases
* Create and configure API endpoints
* Monitor usage and settings

---

### 2. Dashboard Backend

**Repository:** [https://github.com/dblayer-dev/dashboard.backend.dblayer.dev](https://github.com/dblayer-dev/dashboard.backend.dblayer.dev)

Implements backend APIs required for the dashboard to function, including:

* User and project management
* Dashboard-specific business logic
* Configuration handling

---

### 3. API

**Repository:** [https://github.com/dblayer-dev/api.dblayer.dev](https://github.com/dblayer-dev/api.dblayer.dev)

Core engine of DBlayer responsible for:

* Processing user-defined APIs
* Connecting securely to user databases
* Executing queries and returning results
* Enforcing access and execution rules

---

### 4. App

**Repository:** [https://github.com/dblayer-dev/app.dblayer.dev](https://github.com/dblayer-dev/app.dblayer.dev)

Contains the UI/UX for the DBlayer App feature, allowing users to:

* Build custom interfaces (tables, buttons, inputs, etc.)
* Create interactive views on top of database data
* Use DBlayer as a lightweight app builder

---

### 5. Configs

**Repository:** [https://github.com/dblayer-dev/config.dblayer.dev](https://github.com/dblayer-dev/config.dblayer.dev)

Includes server and environment configuration files required to run:

* DBlayer backend services
* API infrastructure

---

### 6. Worker

**Repository:** [https://github.com/dblayer-dev/worker.dblayer.dev](https://github.com/dblayer-dev/worker.dblayer.dev)

Contains background worker scripts used for:

* Asynchronous processing
* Scheduled jobs
* Supporting internal platform operations

---

### 7. Status

**Repository:** [https://github.com/dblayer-dev/status.dblayer.dev](https://github.com/dblayer-dev/status.dblayer.dev)

Implements the public status and health monitoring page for DBlayer.
Initially integrated with external cron-based uptime monitoring.

---

### 8. Docs

**Repository:** [https://github.com/dblayer-dev/docs.dblayer.dev](https://github.com/dblayer-dev/docs.dblayer.dev)

Contains all official documentation, including:

* Platform concepts
* Setup guides
* API usage
* Best practices
