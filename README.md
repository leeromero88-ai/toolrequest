# ToolRequest

Request tools without verbal requests. Nothing gets lost.

**Tools only.** No maintenance - maintenance already exists at work.

Live demo: https://toolrequest-eight.vercel.app

## What it solves
Today tool requests are verbal, by message, or by expiring link. They get forgotten.
Work only speeds up if work stops and workers say they cannot continue without the tool.

ToolRequest puts every request in one place, with status.

## How it works

### 👷 WORKER
1. Writes who is requesting, what tool, for what job
2. Adds estimated cost and supplier: 【entity-MSC¦canonical_name=MSC】, 【entity-Amazon¦canonical_name=Amazon】, Grainger
3. Pastes the product link from 【entity-MSC¦canonical_name=MSC】 (mscdirect.com) or 【entity-Amazon¦canonical_name=Amazon】
4. Chooses urgency: Normal / Urgent / URGENT - WORK STOPPED
5. Taps Create Request

### 👀 SUPERVISOR
1. Sees all requests in one dashboard
2. Sees totals: Total / Urgent / Delivered
3. Sees department budgets: Welding, Machining, Assembly, Maintenance
4. Opens the store link with one tap - MSC, Amazon, Grainger
5. Taps Approve / Delivered / Pending to update status

## Suppliers
- MSC - mscdirect.com - Search directly from the app, copy product link like https://www.mscdirect.com/product/details/09255092
- Amazon
- Grainger

## Languages
English | Español | Kreyòl | Français
Worker requests in their language, supervisor sees it in theirs.

## Tech
- Single file: index.html
- Hosted on Vercel (free Hobby)
- Code stored on GitHub

Built by Lee Romero - Pilot v1