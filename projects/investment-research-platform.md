---
title: "Investment research subscription platform"
url: "https://kremnyi.com/projects/investment-research-platform"
description: "Investor dashboard with free research screens and a Stripe paywall for premium data."
author: "Bohdan Kremnyi"
---

# Investment research subscription platform

> Published at [kremnyi.com/projects/investment-research-platform](https://kremnyi.com/projects/investment-research-platform).

Investor dashboard with free research screens and a Stripe paywall for premium data.

## Delivery challenge

Market feeds and scraped company data had to power the same screens without mixing free access with paid data.

## My role

Split premium into data access, chart refresh, and upgrade steps. Kept client-supplied API signals separate from data the team had to scrape and normalize.

## What shipped

Dashboard live with stock charts, earnings, and research signals; premium access gated through Stripe.

- Signals from web traffic, Twitter, LinkedIn, and news sentiment
- Distributed scraper that rotates accounts and rests banned ones for 48 hours
- Premium prices refreshed every minute

**Engagement:** 3.5-year client relationship (2020–2023)

**First MVP:** 2021

**Customer market:** UK

## Technology

Stripe, REST APIs, web scraping, financial data visualization, distributed scraper workers
