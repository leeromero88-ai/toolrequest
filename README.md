# ToolRequest - Tool Request System

## What it is
Web system to request tools in a factory / shop without verbal requests, without lost chat messages, and without expiring links.

## How it works
- Worker scans QR of their department -> enters already as Worker, already in their department, already with their supervisor.
- Requests a tool in 30 seconds: what, for what job, urgency.
- Supervisor sees dashboard, moves requests: Pending / In Review / Approved / Purchased / Delivered / Rejected.
- URGENT - WORK STOPPED: request in red, on top, with stopped-time counter.
- Languages: English, Spanish, Haitian Creole, French. Worker requests in their language, supervisor sees it in theirs.
- Budget per department: assigned, spent, available, alerts at 80% and 100%.
- QR per department + QR per machine for maintenance ticket.

## Where it lives
Not an App Store / Play Store app. It is web. Hosting: Vercel / Netlify. Database: Supabase / Firebase.

## Current status
Prototype / Demo to validate the idea. Missing for production:
1. Real login (worker + supervisor)
2. Real WhatsApp Business
3. Connection to existing maintenance system
4. Final domain + printed QR codes

## How to run the pilot
1. Choose 1 department (e.g. Welding)
2. Print its QR and put it on the wall
3. 2 weeks of testing, measure waiting time and work-stopped cases