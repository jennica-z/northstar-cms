
# Northstar CMS

A lightweight content workspace built with Django CMS.

Northstar CMS is a small publishing and content management workspace focused on pages, notes, and structured content organization. The project is intentionally kept simple and optimized for local development.

## Features

- Page management with Django CMS
- Visual content editing
- Flexible plugin-based page layouts
- Static asset support
- Lightweight local setup

## Quick Start

Build:

docker build -t northstar-cms .

Run:

docker run -p 8000:8000 northstar-cms

Open in browser:

http://localhost:8000

Admin panel:

http://localhost:8000/admin

Create administrator:

docker exec -it <container_id> python manage.py createsuperuser

## Development Notes

This repository is simplified for local development:

- SQLite enabled by default
- No external database required
- Single-container deployment
- No cloud platform dependency
- Local-first workflow

This keeps setup small and reproducible while preserving the core CMS experience.