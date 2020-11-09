# Project status
![](https://img.shields.io/badge/status-ongoing-green)

# Security by Design

This is an ongoing project that is about designing an architecture with focus on security. The final design is not a definite answer, but can be seen more like suggestion(s) on implementing security methods.

# Motivation

The motivation about this project is to learn more about how I can be more aware of possible security issues, and to train my process of thinking with security in mind when planning/creating an architecture.

# Description

A system that tracks books, authors, and their many-to-many relationship. Typical CRUD-type application.

## Security questions

* How will the data be protected?
* How will the security goals (CIA) be realized?
* What other services are involved? For each:
  - How will they be communicated with?
  - For what purpose?

# App- /Web-client

The frontend client will have the ability to let a user search on a book and/ord author. The obvious thing here is to implement input santization in order to prevent XSS and SQL-Injection ([OWASP's Top 10 Vulnerabilities](https://owasp.org/www-project-top-ten/)).
