## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Assignment requirements

The developer received this instructions:
```
# Coding Challenge - Pokedex

- Required technologies: TypeScript, GraphQL, Next.js

## Task

Create a web-based client for https://pokeapi.co/​ that allows users to list and view details of all the first generation Pokemon.

## Requirements

- The application should be implemented using NextJS with TypeScipt.
- The application should be responsive and work on mobile devices.
- The application should use the GraphQL API provided by https://pokeapi.co/​.
- The application should be developed as if it were a production application. This means that the code should be clean, maintainable, with simple but useful git history messages.

Recommended but not mandatory: Use Tailwind CSS for styling.
BONUS: The application looks pretty and is easy to use. 🦄

### The UI

Implement a frontend that contains the following functionality:

- Initial page should load a paginated list of all the first generation Pokemons.
- The list should show the name and image of each Pokemon.
- Ability to filter the list by name (search input) and type (select input).
- Clicking on a Pokemon should open a detail page that shows the following information:
  - Name
  - Image
  - Types
  - Stats (HP, Attack, Defense, Special Attack, Special Defense, Speed)
  - Evolution chain (if available)
  - List of abilities (if available)
```
