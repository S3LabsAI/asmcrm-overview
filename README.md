# ASM CRM Beta Overview

A one-page overview of the ASM CRM Beta Mac app: its pages and features, how it works, where its information comes from, and the GOAL data access review of 11 Nov 2026.

The whole site is `index.html`. It has no build step and no dependencies apart from two Google Fonts.

## View it locally

Open `index.html` in a browser.

## Deploy on Vercel

1. In Vercel, choose **Add New → Project** and import `S3LabsAI/asmcrm-overview`.
2. Leave **Framework Preset** on **Other**, and leave the build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys.

`vercel.json` turns on clean URLs and sends a `noindex` header, so search engines are asked not to list the page. Anyone with the link can still open it.
