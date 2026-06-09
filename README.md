# budibase-logistics-app

Internal logistics and analytics application built with Budibase, backed by a multi-schema PostgreSQL database. Part of a team project at WWTradeGroup LLC (Amazon e-commerce).

## What this does

A single internal app covering several business areas:

**3PL Operations**
Tracks inventory movements between warehouses — China → US warehouses → FBA/AWD. Each operation has a type (bundle assembly, transfer, shipment), source and destination warehouse, quantity, ETA, and status.

**Shipments Change Log**
Audit trail for shipment status changes. Shows what changed, when, and the full diff in JSON format. Useful for tracking FBA receiving progress.

**PPC Campaign Dashboards**
Several dashboard pages for Amazon advertising analytics — by product, by campaign, by marketplace (US/CA).

**Other modules**
Sales analytics (customizable periods), removal orders, product/SKU management, keyword tracking.

## Stack

- [Budibase](https://budibase.com) — frontend / app builder
- PostgreSQL — backend database (14 schemas, 33+ tables in the reference schema)
- N8N — data pipelines feeding the database

## Screenshots
![Title](https://github.com/FelAnalyst/budibase-logistics-app/blob/main/screenshots/1.jpg)
![3PL Operations — edit form](https://github.com/FelAnalyst/budibase-logistics-app/blob/main/screenshots/3pl-edit.jpg)
![Shipments Change Log](https://github.com/FelAnalyst/budibase-logistics-app/blob/main/screenshots/change_log.jpg)

## Notes

This is a documentation-only repository — Budibase apps are not exported as portable code. Screenshots and descriptions show the structure and functionality of the app.

Product names, SKUs, and other business data have been blurred in all screenshots.
