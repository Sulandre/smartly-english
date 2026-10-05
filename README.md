# Smartly English

Full-stack ESL learning, booking, e-commerce and student support platform built with Next.js, TypeScript, Spring Boot and PostgreSQL.

## Overview:

Smartly English is an all-in-one English learning platform designed to bring teaching, learning, scheduling, pyments, communication, support and business mangement into one ecosystem.

The platform is designed around a complete student journey:

Visitor -> Registration -> Assessment -> Trail -> Recommendation -> Purchase -> Enrollment -> Lessons -> Learning -> Progress -> Feedbck -> Complete -> Certificate

## Core Features

- Public marketing website
- Student portal
- Teacher portal
- Admin portal
- English assessment and placement
- Course catalog
- Course enrollment
- Group classes
- Private lessons
- Scheduling and calendar
- Attendance
- Learning materials
- Homework
- Lesson recordings
- Student progress tracking
- Teacher feedback
- Stripe payments
- Manual/Wise pyment workflow
- Student messaging
- Support tickets
- AI support
- Knowledge base
- Reviews
- Certificates
- Notifications
- CRM
- Analytics
- Audit logging

## Technology stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui
- React Hook Form
- Zod
- TanStack Query

### Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- Bean Vlidation
- REST API

### Database

- PostgreSQL
- Flyway

### Intergrations

- Supabase Auth
- Supabase Storage
- Stripe
- Zoom
- AI/LLM APIs
- Transactional email provider

### Testing

- JUnit
- Spring Boot Test
- Playwright

### CI/CD

- GitHub Actions

## Architecture

```text
Web / Mobile
     |
     v
Next.js Frontend
     |
 HTTPS / REST
     |
     v
Spring Boot API
     |
     +-------------------+
     |                   |
     v                   v
PostgreSQL           File Storage
     |
     +-------------------+
     |
     +--> Stripe
     +--> Zoom
     +--> AI
     +--> Email
