# Allegro Finance Sync

Internal reporting integration for Allegro REST API.

## Purpose

The application synchronizes selected read-only financial and order data
from authorized Allegro seller accounts to internal reporting tools.

## Data used

- seller payouts
- billing entries and fees
- payment refunds
- orders and sales totals

## OAuth scopes

The application uses read-only permissions:

- allegro:api:billing:read
- allegro:api:payments:read
- allegro:api:orders:read

The application does not create or modify offers, orders, payments or refunds.

## Authentication

Each Allegro seller account explicitly authorizes access through OAuth 2.0.

Credentials and OAuth tokens are stored privately and are never published
in this repository.

## Usage

Private internal business reporting and financial reconciliation.

## Version

1.0
