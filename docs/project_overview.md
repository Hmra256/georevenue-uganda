# GeoRevenue Uganda

## Project Overview

GeoRevenue Uganda is a GIS-enabled local government property mapping and revenue management system designed to help local authorities register taxable properties, capture GPS coordinates, manage taxpayers, generate bills, monitor payments, and improve local revenue collection.

---

# Problem Statement

Many local governments face challenges such as:

- Unregistered taxable properties
- Poor property tracking
- Incomplete taxpayer records
- Weak field verification systems
- Revenue leakage
- Lack of GIS-enabled mapping
- Limited reporting and analytics

This system aims to solve these challenges through digital property mapping and revenue administration.

---

# MVP Features

## Authentication
- User login
- Role-based access

## Property Registration
- Register taxable properties
- Capture GPS coordinates
- Upload property photos

## Taxpayer Management
- Register taxpayer information
- Link taxpayers to properties

## GIS Mapping
- Display mapped properties
- Coordinate storage using PostGIS

## Dashboard
- View properties
- Basic analytics and reports

---

# User Roles

| Role | Responsibility |
|------|----------------|
| Admin | Full system management |
| Revenue Officer | Register and inspect properties |
| Finance Officer | Billing and revenue monitoring |
| Auditor | Review logs and reports |
| Taxpayer | View bills and payment status |

---

# Proposed Tech Stack

| Layer | Technology |
|------|-------------|
| Mobile App | Flutter |
| Backend APIs | Golang |
| GIS Database | PostgreSQL + PostGIS |
| Web Dashboard | Angular |
| Additional Services | Python |
| Version Control | Git |

---

# Basic System Flow

Field Officer → Property Registration → GPS Capture → Property Photos → Taxpayer Linking → Billing → Payment → Dashboard Reporting

---

# Month 1 Goals

- Setup project structure
- Design database schema
- Setup backend APIs
- Create Flutter starter app
- Setup Angular dashboard
- Enable GIS support with PostGIS
- Build authentication system
- Build property registration module