# Site Navigation

Use this skill when an agent needs to find public SAIGON EDTECH website resources.

## Inputs

- `intent`: The user's public information goal, such as pricing, product capabilities, contact details, legal terms, or privacy information.
- `locale`: Optional locale preference. Use `vi` for Vietnamese or `en` for English when available.

## Procedure

1. Start at `https://sgedtech.com/` for the default Vietnamese homepage.
2. Use `https://sgedtech.com/en/` when the user asks for English content.
3. Prefer these public routes for common goals:
   - Product overview: `/`
   - Pricing: `/pricing`
   - FAQ: `/faq`
   - Contact: `/contact`
   - Privacy policy: `/privacy`
   - Terms: `/terms`
4. If the agent requests Markdown, send `Accept: text/markdown` for the homepage.

## Boundaries

This skill only covers public website navigation. It does not grant access to customer data, protected SEMS portals, payments, or administrative actions.
