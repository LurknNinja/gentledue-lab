# GentleDue — browser-only invoice reminder drafts

GentleDue is a free early prototype for freelancers who want respectful overdue-invoice follow-up drafts. It runs entirely in the user's browser and stores saved invoice entries only in that browser's localStorage. No emails are sent, no tracking scripts are included, and no payment details are collected by this website.

**Prototype only.** Drafted reminder language is not legal advice. Check the original invoice, contract and applicable law before sending. Export your data as CSV if you want a backup.

## Deploy to Render

Use Render **Static Site** with:
- Repository: `https://github.com/LurknNinja/gentledue-lab`
- Branch: `main`
- Build command: `echo 'GentleDue static build ready'`
- Publish directory: `public`
- Auto deploy: enabled

A `render.yaml` is included for Render Blueprint deployments if desired. Do not provision a paid web service; this is a static site.

## Included features

- Client / invoice amount / due date fields
- Tone-aware follow-up email draft templates
- On-device saved invoice list with mark-paid / remove
- Export invoice list as CSV and a follow-up reminder as ICS calendar event

This first release uses deterministic templates, not paid AI API calls. No checkout or paid plan is available. Development is part of a zero-upfront-cost experiment; verify live product behavior before promoting it.
