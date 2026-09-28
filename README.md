# Ulusal24 Assets CDN

Public static asset repository for **ulusal24.com**.

CDN base:
`https://cdn.jsdelivr.net/gh/mkaanmete/Ulusal24-Assets@main/`

## Structure
- `brand/` logos and brand assets
- `icons/` UI icons
- `images/ui/` permanent interface imagery
- `images/defaults/` fallback/editorial placeholders
- `maps/` static geographic assets
- `fonts/` licensed web fonts only

## Rules
This repository is for permanent **static UI assets only**.
Do not store news uploads, user uploads, generated editorial media, secrets or environment files here.

Production releases should use immutable version tags instead of `@main`.
