# Adaptive Personal Finance

An AI-powered personal finance app that starts as a simple expense tracker and adapts to each user's needs.

Instead of forcing users into predefined budgeting systems, AI helps them build and evolve their own financial structure based on their income, spending habits, and financial goals.

The long-term vision is to evolve from expense tracking into personal financial intelligence, helping users understand their cash flow, anticipate financial challenges, and make better financial decisions.

## Tech Stack

| Layer | Technology |
|---|---|
| AI Coding Agent | Devin |
| Frontend | Expo + React Native |
| Language | TypeScript |
| Navigation | Expo Router |
| Server State | TanStack Query |
| Forms & Validation | React Hook Form + Zod |
| Backend | Supabase |
| Database | PostgreSQL |
| Authentication | Supabase Auth |
| Serverless Functions | Supabase Edge Functions |
| AI Integration | LLM API with structured outputs and tool calling |

## Architectural Principles

- Mobile-first, modular, and maintainable architecture.
- PostgreSQL as the single source of truth for financial records.
- JSONB for flexible, user-specific financial configurations.
- AI-assisted financial organization with schema-validated outputs.
- Deterministic application logic for all financial calculations.
- Stateless AI orchestration with persisted conversation context.
- Row Level Security (RLS) for user data isolation.
- Provider-independent AI integration to support future model changes.

## Development Philosophy

Start simple, validate early, and expand based on actual user needs.

Avoid premature abstractions, unnecessary dependencies, and overengineering. Build a reliable financial foundation before introducing more advanced AI capabilities.
