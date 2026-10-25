# Web Traffic Analytics — Google Analytics 4

## Project Overview

This project analyzes website traffic and user behavior using Google Analytics 4 (GA4) demo data from the Google Merchandise Store.

The goal is to understand website performance, identify popular pages and traffic sources, analyze user journeys, and investigate potential drop-off points in the purchase funnel.

## Tools Used

- Google Analytics 4 (GA4)
- GA4 Reports and Explorations
- Funnel Exploration
- Path Exploration
- GitHub

## Analysis Period

September 27 – October 24, 2026

## Key Metrics

| Metric | Result |
|---|---:|
| Total views | 524,808 |
| Total active users | 97,093 |
| Views per active user | 5.41 |
| Average engagement time per active user | 1 minute 17 seconds |
| Sessions | 132,868 |
| Engaged sessions | 58,530 |
| Engagement rate | 44.05% |

## Popular Pages

The Pages and Screens report identified the following high-traffic pages:

| Page | Views | Active users |
|---|---:|---:|
| Home (`/`) | 113,088 | 79,667 |
| New arrivals (`/shop/new`) | 27,360 | 11,313 |
| Checkout (`/checkout`) | 27,307 | 5,720 |
| Men's / Unisex (`/shop/apparel/mens`) | 25,385 | 9,252 |
| Clearance (`/shop/clearance`) | 19,072 | 8,317 |

The Home page received substantially more views than the other listed pages.

## Traffic Acquisition

Organic Search was the largest traffic channel visible in the report, with 32,860 sessions and an engagement rate of 70.71%.

Other visible channels included:

- Referral: 3,164 sessions
- Unassigned: 7,060 sessions, with an engagement rate of 11.25%
- Organic Social: 710 sessions, with an engagement rate of 75.77%
- Organic Shopping: 477 sessions, with an engagement rate of 83.23%

Organic Shopping had the highest engagement rate among these displayed channels, although its session count was relatively small.

## Funnel Exploration

The purchase funnel included four stages:

| Funnel step | Users |
|---|---:|
| View product | 23,299 |
| Add to cart | 6,927 |
| Begin checkout | 3,705 |
| Purchase | 1,964 |

The largest drop-off occurred between viewing a product and adding it to the cart. A total of 16,372 users dropped off at this stage, representing 70.27% of users in the first step.

A further 3,222 users dropped off between adding an item to the cart and beginning checkout.

These results identify stages that deserve further investigation but do not establish the causes of drop-off.

## User Journey Analysis

Path Exploration showed that Home was a common page after a session started. Users then navigated to shopping pages such as New arrivals, the 1998 Retro Collection, Men's / Unisex, and Sale.

The checkout path also showed events such as `add_shipping_info`, `page_view`, and `add_payment_info` after `begin_checkout`.

Path Exploration event counts should not be interpreted as unique users or confirmed purchase abandonment without additional analysis.

## Recommendations

1. Investigate product pages to understand why many visitors do not proceed to add items to their carts.
2. Review the checkout experience for usability issues, unexpected costs, or unnecessary steps.
3. Improve navigation between the Home page and product categories.
4. Investigate the Unassigned traffic channel to understand why sessions are not being categorized clearly.
5. Continue monitoring engagement and purchase-funnel metrics over time.

## Screenshots

Screenshots of the GA4 reports are available in the `screenshots/` folder.

## Data Source

Google Analytics 4 demo account — Google Merchandise Store.

The analysis uses the read-only demo data provided by Google Analytics for learning and reporting practice.
