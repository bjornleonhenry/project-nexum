# Project Nexum

A modern wiki and knowledge management platform built with SvelteKit, featuring AI-powered content generation and collaborative editing.

## Features

- 📚 Wiki-style knowledge base
- 🤖 AI-powered content generation with OpenAI
- 👥 Collaborative editing and team management
- 🎨 Rich text editing with TinyMCE
- 📊 Content analytics and read time estimation
- 📱 Responsive design for all devices
- 🔒 Secure authentication and permissions

## Tech Stack

- **SvelteKit** - Full-stack web framework
- **PocketBase** - Backend and database
- **OpenAI** - AI content generation
- **TailwindCSS** - Utility-first styling
- **DaisyUI** - Component library
- **TinyMCE** - Rich text editor
- **Zod** - Schema validation

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- pnpm package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd project-nexum
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your OpenAI API key and other configuration
```

4. Start the development server:
```bash
pnpm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
pnpm run dev

# or start the server and open the app in a new browser tab
pnpm run dev -- --open

# you can also host your dev session on your local network, allowing you to test on other devices. Use --host to specify the host you want to use:

pnpm run dev --host
```

## Building

To create a production version of your app:

```bash
pnpm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
