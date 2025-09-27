# AI-Powered Resume Analyzer

**Technologies:** React, React Router v7, Puter.js, Tailwind CSS, TypeScript, Vite, Zustand  
**Description:** Build an AI-driven resume analyzer that handles authentication, resume storage, and smart candidate-to-job matching (e.g. ATS scoring, feedback) — all with no backend infrastructure required thanks to Puter.js.

---

## 🚀 Features

- **Zero-backend auth**: Authentication fully handled in the browser using Puter.js  
- **Resume upload & storage**: Users can upload and manage multiple resumes securely  
- **Smart matching & scoring**: Analyze a resume against a job listing and receive an ATS score + custom feedback  
- **Reusable modern UI**: Clean, modular components for consistency and maintainability  
- **Responsive & cross-device**: Works seamlessly on desktop, tablet, and mobile  
- **State management**: Uses Zustand for minimal, high-performance global state  
- **Modern toolchain**: Built with TypeScript, Vite, Tailwind CSS (and optionally shadcn/ui)  
- **Code reuse focused**: Modular architecture to encourage reuse and maintainability  

---

# Welcome to React Router!

A modern, production-ready template for building full-stack React applications using React Router.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/remix-run/react-router-templates/tree/main/default)

## Features

- 🚀 Server-side rendering
- ⚡️ Hot Module Replacement (HMR)
- 📦 Asset bundling and optimization
- 🔄 Data loading and mutations
- 🔒 TypeScript by default
- 🎉 TailwindCSS for styling
- 📖 [React Router docs](https://reactrouter.com/)

## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
