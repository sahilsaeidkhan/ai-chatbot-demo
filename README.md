# Website Chatbot — a small demo

A little chatbot widget I built for business websites. It sits on the page, answers the questions visitors ask again and again — timings, prices, services — takes a name and email when someone wants a quote, and hands the chat over to WhatsApp or email the moment it gets stuck.

No backend, no build step. It's one HTML file, and I kept it that way on purpose: it loads instantly, costs nothing to run, and drops into an existing website in minutes.

**Try it live:** https://sahilsaeidkhan.github.io/ai-chatbot-demo/

## What it does

- Answers common questions straight from a FAQ list you control
- Lead capture — a visitor types "interested" and it politely takes their name and email
- Human handoff — WhatsApp and email buttons show up whenever the bot can't answer, so a real conversation never dies inside a bot
- Works on phones, zero dependencies, nothing to install

## Make it yours

Open `index.html` and find the `CONFIG` block near the top of the script. Add your business name, contact email, a WhatsApp number if you want that button, and your own questions and answers. Save the file, put it on your site — that's genuinely all there is to it.

## Why keyword matching?

Honest answer: on a small business website, almost every question is one of the same ten questions. A small, predictable matcher answers those instantly and never invents a price or a timing. For anything beyond that, it hands over to a human instead of making things up — which is exactly the behaviour I'd want on my own website.

## Where it could go next

- Send captured leads straight to an inbox or CRM
- Optional AI fallback for open-ended questions
- Hindi + English replies

---

Built by Sahil Saeid — I make chatbots and small AI tools for businesses.
GitHub: https://github.com/sahilsaeidkhan
