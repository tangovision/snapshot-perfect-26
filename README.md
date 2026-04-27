# Snapshot Perfect 26

Mobile-first shopping mall companion app built with Vite, React, TypeScript, Tailwind CSS, and shadcn/ui.

## Features

- Home dashboard with mall selector and quick actions
- Store listings and store detail pages
- Events listing and event details
- Cinema browsing, seat selection, and payment flow
- Loyalty and profile screens

## Tech Stack

- React 18 + TypeScript
- Vite 5
- Tailwind CSS
- Radix UI + shadcn/ui components
- Framer Motion for UI transitions
- React Router for navigation

## Prerequisites

- Node.js 20+
- npm 10+

## Local Development

```bash
npm install
npm run dev
```

Open the app at the local URL shown by Vite.

## Scripts

- `npm run dev` - start development server
- `npm run build` - create production build
- `npm run build:dev` - create development-mode build
- `npm run lint` - run ESLint
- `npm run preview` - preview production build locally

## Project Structure

```text
src/
  components/      # shared and UI components
  hooks/           # reusable React hooks
  lib/             # utilities
  pages/           # route-level screens
  main.tsx         # app entry point
  App.tsx          # route configuration
```

## Notes

- This repository currently does not include automated tests.
- See `report.md` in the parent workspace root for an external review summary and recommendations.
