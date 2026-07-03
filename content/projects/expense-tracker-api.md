+++
date = '2026-07-03T08:14:16+08:00'
draft = true
title = 'Expense Tracker API'
+++

A full-stack expense tracking web application built with Go. Users can register, log in, and manage expenses through a web interface styled with Pico CSS and enhanced with HTMX for dynamic interactions.

## Tech

- Language: 	Go 1.26
- Web server: 	`net/http` (stdlib) — no framework
- Database: 	PostgreSQL
- SQL layer: 	`sqlc` (type-safe code generation from SQL)
- Templates: 	`a-h/templ` (type-safe HTML templates)
- Auth: 	`golang-jwt/jwt/v5` (JWT via HTTP-only cookies)
- Passwords: 	`bcrypt`
- Frontend: 	HTMX + Pico CSS
- Dev tools: 	`air` (hot reload), templ watch mode
