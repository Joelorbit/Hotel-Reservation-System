# Contributing to Hotel Reservation System (HRS)

Thank you for your interest in contributing to the **Hotel Reservation System (HRS)**! Contributions of all kinds—bug reports, feature requests, documentation improvements, and code enhancements—are welcome and appreciated.

This document outlines the guidelines and processes for contributing to the project to ensure consistency, quality, and smooth collaboration.

---

## Table of Contents

* [Code of Conduct](#code-of-conduct)
* [How Can You Contribute?](#how-can-you-contribute)
* [Getting Started](#getting-started)
* [Development Workflow](#development-workflow)
* [Coding Standards](#coding-standards)
* [Database Changes](#database-changes)
* [Testing Guidelines](#testing-guidelines)
* [Commit Message Guidelines](#commit-message-guidelines)
* [Pull Request Process](#pull-request-process)
* [Reporting Bugs](#reporting-bugs)
* [Requesting Features](#requesting-features)
* [Documentation Contributions](#documentation-contributions)

---

## Code of Conduct

By participating in this project, you agree to maintain a respectful and professional environment. Harassment, discrimination, or unconstructive behavior will not be tolerated.

---

## How Can You Contribute?

You can contribute in several ways:

* Fixing bugs
* Implementing new features
* Improving performance or security
* Refactoring existing code
* Enhancing UI/UX
* Improving documentation
* Reporting issues or suggesting enhancements

---

## Getting Started

### 1. Fork the Repository

Click the **Fork** button on GitHub to create your own copy of the repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/Joelorbit/Hotel-Reservation-System.git
cd Hotel-Reservation-System
```

### 3. Set Up the Project

Follow the setup instructions in the `README.md`, including:

* MySQL database configuration
* Importing `hotel_db.sql`
* Configuring Apache Tomcat in NetBeans
* Running the application locally

Ensure the application runs successfully before making changes.

---

## Development Workflow

1. Create a new branch from `main`:

   ```bash
   git checkout -b feature/short-descriptive-name
   ```
2. Make your changes locally.
3. Test your changes thoroughly.
4. Commit your work using clear commit messages.
5. Push your branch to your fork.
6. Open a Pull Request (PR) to the main repository.

---

## Coding Standards

### Java

* Follow standard Java naming conventions:

  * Classes: `PascalCase.`
  * Methods and variables: `camelCase.`
* Keep servlets focused on request handling; move business logic to DAO or utility classes.
* Avoid hardcoding credentials or configuration values.
* Add comments for complex or non-obvious logic.

### JSP / Frontend

* Minimize Java code inside JSPs.
* Use JSTL and Expression Language (EL) where possible.
* Maintain consistent formatting and indentation.
* Ensure responsiveness when modifying UI components (Tailwind CSS).

---

## Database Changes

If your contribution includes database modifications:

* Update `hotel_db.sql` accordingly.
* Clearly document schema changes in your Pull Request description.
* Ensure backward compatibility where possible.

---

## Testing Guidelines

Before submitting a Pull Request:

* Test all affected features manually.
* Verify:

  * User registration and login
  * Booking creation, update, and cancellation
  * Admin CRUD operations (users, rooms, bookings)
* Ensure no existing functionality is broken.

---

## Commit Message Guidelines

Use clear, concise, and descriptive commit messages.

**Format:**

```
Type: Short description
```

**Examples:**

* `Fix: Resolve null pointer in BookingServlet.`
* `Add: Admin room availability filter.`
* `Update: Improve validation on user registration.`

Common types:

* `Add`
* `Fix`
* `Update`
* `Refactor`
* `Docs`

---

## Pull Request Process

1. Open a Pull Request against the `main` branch.
2. Include:

   * A clear summary of the changes
   * The problem being solved or feature being added
   * Screenshots (if UI-related)
3. Ensure:

   * The project builds successfully
   * No unnecessary files are included
4. Address any feedback or requested changes promptly.

---

## Reporting Bugs

If you find a bug:

1. Check existing issues to avoid duplicates.
2. Open a new issue and include:

   * Clear steps to reproduce the issue
   * Expected vs actual behavior
   * Screenshots or logs (if applicable)
   * Environment details (OS, browser, Java version)

---

## Requesting Features

Feature requests are welcome. When submitting one:

* Clearly describe the problem or use case.
* Explain how the feature would benefit users or administrators.
* Provide mockups or examples if applicable.

---

## Documentation Contributions

Improvements to documentation are highly valued. This includes:

* README enhancements
* Setup clarification
* Code comments
* Screenshots or diagrams

Ensure documentation changes are accurate and consistent with the current codebase.

---

## Final Notes

This project is primarily a learning and demonstration system built with Java Servlets and JSP. Contributions that improve code quality, maintainability, and clarity are especially encouraged.

Thank you for helping improve the **Hotel Reservation System (HRS)**. Your contributions make this project better for everyone.
