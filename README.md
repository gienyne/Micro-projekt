![Vue.js](https://img.shields.io/badge/Vue.js-Frontend-4FC08D?logo=vue.js&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-Backend-7F52FF?logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-Framework-6DB33F?logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Metadata-4169E1?logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-Analytics-FFCC01)
![S3 Storage](https://img.shields.io/badge/S3-Object_Storage-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

# MICRO – Analytics and Filesystem Platform

## Overview

As part of a university project, a scalable analytics and filesystem solution was developed for the learning platform **MICRO**.

MICRO enables students to execute their own code directly on real hardware (microcontrollers) without requiring physical access to the devices. The hardware is accessible through a centralized infrastructure and is available almost around the clock.

The goal of the project was to efficiently and scalably implement both user file management and the analysis of system and usage data.

---

## Features

### Filesystem

- User-based file explorer (upload, download, folder structure)
- File versioning (history preserved while displaying the active version)
- Prototype file-sharing functionality
- Separation of metadata and file content for improved scalability

### Analytics Dashboard (Admin)

- Visualization of usage and system data
- Analysis categories:
  - User activity
  - Hardware stations
  - File usage
  - Error analysis
- Dynamic charts with selectable time ranges
- Support for monitoring and early error detection

---

## Architecture

The application was designed with a strong focus on scalability, maintainability, and clear system separation.

### Technologies

- Frontend: Vue.js
- Backend: Kotlin with Spring Boot
- Containerization: Docker

### Data Storage

- PostgreSQL: Storage of file metadata
- ClickHouse: Analysis of large-scale usage data
- Garage S3: Scalable object storage for files

By combining multiple storage systems, the platform efficiently handles both transactional and analytical workloads.

---

## Technical Focus Areas

- Development and design of REST APIs
- Integration of multiple specialized database systems
- Processing and analysis of large data volumes
- Scalable storage architecture
- Containerized development and runtime environment

---

## Project Context

This project was developed as part of the *Software Engineering Project* module at the Technical University of Applied Sciences Mittelhessen.

The implementation was carried out by a team of seven people, divided into frontend and backend development.
The developed features were integrated and evaluated in an experimental environment.
A possible productive integration into the platform remains subject to the decision of the project supervisors.

## Status

 Functional prototype with a focus on architecture, data analytics, and system design.

