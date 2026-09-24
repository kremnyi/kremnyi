---
title: "AI greeting-card product"
url: "https://kremnyi.com/projects/ai-greeting-card-product"
description: "Greeting-card generator that keeps the original prompt, four image options, and an order if the buyer leaves before adding contact details."
author: "Bohdan Kremnyi"
---

# AI greeting-card product

> Published at [kremnyi.com/projects/ai-greeting-card-product](https://kremnyi.com/projects/ai-greeting-card-product).

Greeting-card generator that keeps the original prompt, four image options, and an order if the buyer leaves before adding contact details.

## Delivery challenge

The generation flow had to preserve the original prompt and outputs, allow user edits, and keep an order record even when the customer left before entering contact details.

## My role

Specified how recipient and style become a prompt, how templates are edited in Django Admin, and that the first generation creates the order. User edits sit beside the original outputs.

## What shipped

Generation flow with Django Admin templates, four image variants, and editable text. Payment and fulfillment were out of scope.

**First MVP:** 2023

**Customer market:** USA

## Technology

ChatGPT API, DALL-E API, Midjourney, Django Admin
