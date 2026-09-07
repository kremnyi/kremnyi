---
title: "Approck: marketplace, acquisition operations, and forecasting"
url: "https://kremnyi.com/projects/approck-marketplace-fund"
description: "Product & Growth Manager owning marketplace delivery, acquisition operations, and internal tools, with hands-on implementation and developer coordination."
author: "Bohdan Kremnyi"
---

# Approck: marketplace, acquisition operations, and forecasting

> Published at [kremnyi.com/projects/approck-marketplace-fund](https://kremnyi.com/projects/approck-marketplace-fund).

Product & Growth Manager owning marketplace delivery, acquisition operations, and internal tools, with hands-on implementation and developer coordination.

## Delivery challenge

Seller data, listing preparation, acquisition analysis, and investor reporting needed repeatable workflows while the public marketplace stayed live.

## My role

Owned product delivery and contributed hands-on development across the public marketplace and internal acquisition tools while coordinating developers. Built a CRM for application records, shared contacts, verification evidence, and listing preparation, with role-based access and activity history. Developed cohort forecasting with RevenueCat, Adapty, and Apphud, including a mode that assumes no new subscribers. Kept seller-reported figures separate from provider metrics in the valuation intake. Managed post-close investor relations, P&L reporting, and payout coordination. Configured GA4, GTM, HubSpot, Apollo, and 7+ other acquisition trackers; built 10+ Python/n8n automations.

## What shipped

- Marketplace with multilingual discovery, revenue filters, SEO, blog, and knowledge base
- Internal CRM with shared contacts, private verification evidence, and listing-image generation
- Seller valuation intake with separate reported and provider-verified metrics
- Subscription cohort forecasts, growth and no-new-subscriber scenarios, and acquisition-review reports
- Due-diligence and transfer checklists, plus post-close investor reporting
- Domain migration without downtime, followed by analytics verification
- 10+ Python/n8n automations for lead research and recurring operations

## Internal acquisition CRM

Built a shared workspace for application records, reusable contacts, listing status, verification evidence, and listing-image preparation. Read-only, editor, and administrator permissions control access and changes; an activity history records updates. The CRM keeps private deal information available to authorized staff alongside the application being reviewed.

## Seller valuation intake

Built an intake that separates founder-reported net MRR from RevenueCat or Adapty metrics verified on the server. Submissions preserve the source and verification status for operator review. The quick estimate uses the founder's net MRR; provider evidence provides context for the subsequent review.

## Subscription forecasting

Built a deterministic cohort forecasting tool with RevenueCat, Adapty, Apphud, and CSV imports. It models weekly, monthly, and annual subscriptions, compares growth scenarios, and includes a no-new-subscriber mode for assessing revenue from the existing subscriber base. Reports expose the assumptions behind revenue, profit, ROI, and acquisition-price scenarios.

Supporting Python and SQL analyses reconcile revenue evidence and test sensitivity to assumptions. Reusable due-diligence and transfer guides document the questions and evidence needed for acquisition reviews and handovers.

## A decision implemented in the model

An incomplete subscription-duration import should not silently turn a weekly model into an acquisition-price estimate for a mixed subscription business. When a selected RevenueCat or Apphud duration split cannot be verified, the tool withholds the acquisition price and explains the missing evidence. Other checks preserve missing retention observations and avoid deducting commission twice from provider-reported net proceeds.

## Commercial results

Across my Approck work: $1m+ in closed investment deals, 50+ acquisitions mediated, and 100+ applications evaluated with full due diligence. Grew the marketplace website from zero to 30k monthly unique users and approximately 100 leads per month.

## Ongoing operations

- Qualify buyers and sellers, prepare app shortlists, and support valuation and due-diligence discussions.
- Coordinate application, infrastructure, analytics, and account-ownership transfers around acquisitions.
- Maintain investor P&L reports, performance updates, and payout coordination after closing.
- Operate acquisition tracking, outreach, and lead-processing workflows while coordinating developers, QA, marketing, and agencies.

## Technology

Next.js, React, TypeScript, PHP/Symfony, JavaScript, Python, SQL, Cloudflare Workers and D1, RevenueCat, Adapty, Apphud, n8n, HubSpot, Apollo, GA4, GTM.
