# MesaReporting
> Klaviyo analytics SaaS for email marketing agencies

## What it does
MesaReporting pulls campaign and flow performance data directly 
from Klaviyo and surfaces it in a clean dashboard — revenue by 
channel, flow message breakdowns, and campaign comparisons in 
one place.

Built for agencies managing multiple Klaviyo accounts who need 
reporting that Klaviyo's native analytics doesn't provide.

## Tech Stack
- **Frontend:** Next.js, TanStack Query
- **Database:** Supabase (PostgreSQL + RLS)
- **Auth & Billing:** Supabase Auth, Stripe
- **Deployment:** Vercel
- **Data Source:** Klaviyo REST API (2026-01-15)

## Key Features
- Cross-account campaign performance views
- Flow accordion with per-message revenue metrics
- Klaviyo sync functions for campaigns, flows, and delivery data
- RPC functions with SECURITY DEFINER for safe data access

## Status
Currently in private beta.
