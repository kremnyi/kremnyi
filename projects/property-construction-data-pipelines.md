---
title: "Property & construction data pipelines"
url: "https://kremnyi.com/projects/property-construction-data-pipelines"
description: "Scraper operation feeding a European real-estate financing marketplace with construction-permit and property data from state registries in 5 countries."
author: "Bohdan Kremnyi"
---

# Property & construction data pipelines

> Published at [kremnyi.com/projects/property-construction-data-pipelines](https://kremnyi.com/projects/property-construction-data-pipelines).

Scraper operation feeding a European real-estate financing marketplace with construction-permit and property data from state registries in 5 countries.

## Delivery challenge

State registries change often enough that the scraper fleet needed continuous operations, not a one-off build.

## My role

Ran the operation end to end: Estonian, Latvian, Lithuanian, Finnish, and German registry scrapers, Docker-ization of the fleet, an AWS account migration with handoff documentation, Pipedrive CRM sync, Slack completion alerts, and ongoing stability and data-quality work.

## What shipped

- Registry scrapers grown from Estonia in 2019 to 5 countries: Estonia, Latvia, Lithuania, Finland, and Germany
- Latvian 4-step chain: building permits, cadastre, land book, company register
- Personal ID codes stripped from land-register data and never stored
- Bulk API for queuing several thousand objects at a time
- Fleet dockerized, then migrated to AWS with handoff docs
- Pipedrive sync and Slack alerts
- Data-quality work against constantly changing registries

## Delivery scale

**Published scale:** 1,200+ hours • 115+ tasks • 5 contributors • 3 departments

Team mix: 4 backend, 1 PM/BA.

**Engagement:** 5+ years continuous delivery (2019–2025)

**First MVP:** 2019

**Customer market:** Estonia

## Technology

Python, Selenium, Docker, AWS, PostgreSQL, Pipedrive, Slack API, Tor, anti-captcha
