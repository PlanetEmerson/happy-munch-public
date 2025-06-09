# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Happy Munch is a static marketing website for a mobile app that helps users make smart dining choices by analyzing restaurant menus. The site consists of three main pages: landing page, privacy policy, and support.

## Architecture

This is a pure static HTML website with:
- No build process or framework
- Inline CSS on each page
- GitHub Pages deployment via CNAME to happy-munch.com
- No JavaScript dependencies or external libraries

## Common Commands

Since this is a static site, there are no build commands. Development workflow:
- Edit HTML files directly
- Preview changes by opening files in a browser
- Deploy by pushing to GitHub main branch (auto-deploys via GitHub Pages)

## Key Files

- `index.html` - Landing page with app features and download buttons
- `privacy.html` - Privacy policy (mentions OpenAI, Supabase, Superwall integrations)
- `support.html` - FAQ and customer support information
- `CNAME` - Contains custom domain configuration

## Design System

- Primary color: #4CAF50 (green)
- System fonts for performance
- Mobile-first responsive design
- All styles are inline within each HTML file