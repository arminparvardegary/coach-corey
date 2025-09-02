# Coach Corey Next.js Starter

This repository contains a starter Next.js project configured with **TypeScript**, **Tailwind CSS**, and an initial setup for **shadcn/ui** components.  

## Features

- **Next.js (App Router)** – Modern React framework with built‑in routing and server‑side rendering.  
- **TypeScript** – Static typing for better reliability and developer experience.  
- **Tailwind CSS** – Utility‑first CSS framework for rapid styling.  
- **shadcn/ui** – Opinionated collection of accessible UI components built with Tailwind and Radix UI.  

> **Note**: This repository only defines the project structure and dependencies.  Since package installation requires network access, the actual `node_modules` are not committed.  After cloning, run `npm install` (or `pnpm install`) locally to install the dependencies.

## Getting Started

1. **Install dependencies** (requires Node.js and npm):

   ```bash
   npm install
   ```

2. **Start the development server**:

   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

## Using shadcn/ui

The project includes dependencies for [shadcn/ui](https://ui.shadcn.com/), but no components are installed yet.  To add components to your app, run the CLI once dependencies are installed:

```bash
npx shadcn-ui@latest add button
```

This will generate the button component under `components/ui` and let you start using it in your pages.

## Structure

- `app/` – Application routes following the App Router paradigm.  
- `components/` – Shared React components.  
- `lib/` – Utility functions (e.g. `cn` helper for class names).  
- `styles/` – Global styles (imported in `app/layout.tsx`).

Feel free to expand this structure to fit your needs.

## License

This project is provided as‑is, without warranty.  See the [LICENSE](LICENSE) file for more details (not included by default).
