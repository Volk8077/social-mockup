# Social Media Reply Center — Client Portal Mockup

A clickable mockup of the client-facing portal for a multi-tenant social media management product.

The portal is what client businesses (Company B) log into. It demonstrates the three-tier comment-handling model and the post-coordination calendar with performance analytics.

## Live demo

Once GitHub Pages is enabled on this repository, the mockup is viewable at:

`https://<your-github-username>.github.io/<repo-name>/`

## What's in here

A single self-contained HTML file (`index.html`) with embedded CSS and a small amount of JavaScript for tab switching. No build step, no dependencies, no backend — open it in any modern browser.

## Sections

**Replies (คอมเมนต์)** — the AI Reply Agent, organized into three tiers:

- **ต้องดูด่วน (high risk)** — flagged for the client's personal attention via LINE. Brief explanation of why it needs them. AI does not draft for these.
- **รออนุมัติ (medium risk)** — AI-drafted replies. Client approves, edits inline, or rejects.
- **ตอบอัตโนมัติแล้ว (low risk)** — auto-sent replies, kept on file for audit.

**Schedule (ตารางโพสต์)** — week-grid calendar of upcoming posts color-coded by content type, plus a past-posts view with full per-post metrics (reach, likes, comments, shares, saves) and a top-performer banner.

## Status

This is a v1 mockup intended for client and stakeholder demos — not connected to any live data.

## Stack (planned for v1 production)

- Airtable (multi-tenant data)
- Make.com (orchestration)
- Claude API (drafting + risk classification)
- Softr (production version of this portal)
- Meta Graph API (Facebook / Instagram)
