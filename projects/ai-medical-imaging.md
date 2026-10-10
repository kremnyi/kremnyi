---
title: "AI medical-imaging app"
url: "https://kremnyi.com/projects/ai-medical-imaging"
description: "Medical product using an ML pipeline to analyze patients' hand photos for joint symptoms, delivered directly inside the client's engineering workflow."
author: "Bohdan Kremnyi"
---

# AI medical-imaging app

> Published at [kremnyi.com/projects/ai-medical-imaging](https://kremnyi.com/projects/ai-medical-imaging).

Medical product using an ML pipeline to analyze patients' hand photos for joint symptoms, delivered directly inside the client's engineering workflow.

## Delivery challenge

Backend work had to fit a client-owned ML codebase and GitHub issue flow.

## My role

Coordinated Celery and RabbitMQ pipeline orchestration, an Azure database migration, API and schema changes, and auth/verification flows in step with the client's in-house ML team.

## What shipped

- AI imaging workflow delivered inside the client's ML codebase
- Hand photos tagged left or right with capture time via EXIF metadata, paired with per-joint symptoms and 1–10 pain and stiffness scores
- Doctor/patient auth and imaging history
- Personal data kept in its own database
- Pipeline orchestration on Celery/RabbitMQ, database moved from AWS RDS to Azure PostgreSQL

## Delivery scale

**Published scale:** 45+ tasks • 3 contributors • 4 departments

Team mix: 2 backend, 1 PM/BA.

**First MVP:** 2023

**Customer market:** Finland

## Technology

Python, Celery, RabbitMQ, Azure, PostgreSQL, ML pipeline integration, GitHub, Django, Docker, Azure App Service, Azure Blob Storage, GitHub Actions
