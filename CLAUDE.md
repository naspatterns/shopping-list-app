# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple Korean-language shopping list web application ("릴라와 함사의 쇼핑 리스트" / Lila & Hamsa's Shopping List). It's a standalone HTML file with embedded CSS and JavaScript - no build tools or package manager required.

## Architecture

- **index.html**: Single-file application containing all HTML, CSS, and JavaScript
  - Uses Supabase for data persistence (shopping_items table)
  - Features a vintage/classic aesthetic with Korean fonts (Noto Serif KR)
  - Dependencies: Supabase JS client (CDN), Google Fonts

## MCP Configuration

The project has Supabase MCP server configured in `.mcp.json`. The access token is stored in `.env` as `SUPABASE_ACCESS_TOKEN`.

## Development

To view the application, simply open `index.html` in a browser. No server or build process is needed.