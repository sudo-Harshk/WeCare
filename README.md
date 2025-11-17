# WeCare Wellness Page

A modern, responsive wellness platform website built with React and TypeScript. WeCare provides information about wellness services, features, pricing, and includes engaging call-to-action sections.

## Project Overview

WeCare Wellness Page is a single-page application showcasing wellness services with a clean, modern design. The application features:

- **Hero Section**: Engaging landing section with key messaging
- **Features**: Highlighted wellness service features
- **Pricing**: Transparent pricing information
- **Call-to-Action**: Conversion-focused CTA sections
- **Responsive Design**: Mobile-first approach with Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v16 or higher) - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- npm (comes with Node.js)

### Installation

Follow these steps to set up the project locally:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm install

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

The development server will start on `http://localhost:5173` (or the next available port).

### Development Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run build:dev` - Build the project in development mode
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Technologies Used

This project is built with modern web technologies:

### Core Stack
- **React 18.3** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and development server
- **React Router** - Client-side routing

### UI & Styling
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn-ui** - High-quality React components built on Radix UI
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icon library

### Additional Libraries
- **TanStack Query (React Query)** - Data fetching and state management
- **React Hook Form** - Form handling with validation
- **Zod** - Schema validation
- **Recharts** - Chart library for data visualization

## Building for Production

To build the project for production:

```sh
# Build for production
npm run build

# Preview the production build locally
npm run preview
```

The production build will be in the `dist/` directory, ready to be deployed to any static hosting service.
