# Project

## App Name

CRM (working name, not final).

## Overview

A Customer Relationship Management system built with PHP (Laravel), Vue.js, Nginx and PostgreSQL. It stores customers, the notes and activity logged against them, and the deals being worked with them, and shows a dashboard of simple stats. It is built as a learning project: the owner has finished the theory and is now learning PHP and Laravel by building something real, in small stages.

## Problem

Customer details, conversations and sales opportunities are easy to lose when they live in scattered notes and spreadsheets. A CRM keeps them in one place. For the owner, the project also solves a second problem: turning PHP theory into practical skill.

## Purpose

Be the owner's main hands-on PHP and Laravel learning project, with enough real-world challenge (relational data, auth, search, roles) to make the skills stick, and with a result usable as a portfolio piece.

## Goals

- Learn PHP and Laravel by building: routing, controllers, Blade views, Eloquent with PostgreSQL, migrations, authentication, validation and escaping output, plus Vue.js for the frontend and Nginx as the web server.
- Keep each stage working and complete before starting the next.
- End with a CRM that can really be used to manage customers and deals.

## Non-Goals

- Not a commercial or multi-tenant product (no billing, subscriptions or multiple companies).
- No email integration, mobile app or third-party API integrations in the first version.

## Target Users

- **Primary:** the owner, as a learner.
- **Intended app users:** a small sales team or a solo business owner (admin and regular user roles).

## Core Features

Planned in stages (order and detail belong in `PHASES.md`, not decided here):

- Setup: Laravel project, Nginx, PostgreSQL connection, Vue.js frontend, shared layout.
- Authentication: register, login, logout.
- Customers: add, view, edit and delete.
- Search and pagination.
- Notes and activity log per customer (calls, meetings).
- Deals pipeline (Lead, Negotiation, Won, Lost).
- Dashboard with totals and simple stats.
- Roles: admin and regular user.

## Current Status

Not started. Only the folder `C:\learning\CRM`, a README note and these docs exist. No Laravel project or database yet. Whether PHP, Composer, Node.js, Nginx and PostgreSQL are installed on the owner's machine has not been checked.

## Constraints

- Stack: PHP + Laravel (backend), Vue.js (frontend), Nginx (web server), PostgreSQL (database).
- Runs locally on Windows 11.
- Built by a learner, so clarity matters more than cleverness; work is done in small steps.
- Must follow the rules in `CLAUDE.md`, including no commit or push and no deleting without asking the owner.

## Scope

In scope: the features under Core Features. Out of scope: everything under Non-Goals. Anything else needs the owner's decision first.

## Success Criteria

- Every planned stage works end to end in the browser.
- The owner understands the code written and can explain how it works.
- User input is validated and output is escaped, and passwords are hashed.
- The docs match the real state of the project.
