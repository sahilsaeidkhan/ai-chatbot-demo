# Chatbot demo (single-file template)

`index.html` is a self-contained, no-backend chatbot demo — open it in any browser, or host it anywhere (GitHub Pages, Netlify, Vercel).

## Customize per client in ~2 minutes
1. Edit the `CONFIG` block at the top of the `<script>`:
   - `businessName`, `whatsapp` (digits only, e.g. "919876543210"), `email`
   - `faqs`: replace with 5–8 real Q&As scraped from the client's website; `k` = keyword triggers
2. Save, screenshot/screen-record it, and send the link in the gig DM.

## What it does
- Answers FAQs with simple keyword matching
- Lead capture flow ("interested" → asks name → asks email)
- Human handoff: WhatsApp + email buttons when it can't answer

Built 2026-10-20 as a reusable demo asset — backs the free-mini-demo offer made to
Mitesh Garg and fills the standing gap (no chatbot demo existed in his 22 public repos).
