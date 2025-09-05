# Overview

This is a full-stack web application built with React and Express.js, featuring a cyberpunk/hacker-themed design for what appears to be a "Teacher's Day" celebration website. The application showcases a modern tech stack with a Matrix-inspired visual aesthetic, including animated backgrounds, glitch effects, and terminal-style UI components.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript and Vite for fast development and building
- **Styling**: Tailwind CSS with a custom cyberpunk theme featuring Matrix green colors and hacker aesthetics
- **UI Components**: Comprehensive component library based on Radix UI primitives with shadcn/ui styling
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query (React Query) for server state management
- **Animations**: Framer Motion for smooth animations and transitions
- **Design System**: Custom components including MatrixBackground, TerminalWindow, GlitchCard, and TypingEffect

## Backend Architecture
- **Framework**: Express.js with TypeScript running in ESM mode
- **Development**: Hot reloading with tsx for development server
- **Storage Interface**: Abstracted storage layer with in-memory implementation (MemStorage class)
- **API Structure**: RESTful API with `/api` prefix routing
- **Error Handling**: Centralized error handling middleware
- **Logging**: Custom request/response logging for API endpoints

## Data Storage
- **Database**: PostgreSQL configured for production with Neon Database serverless driver
- **ORM**: Drizzle ORM with schema-first approach
- **Schema**: User management system with username/password authentication
- **Migrations**: Drizzle Kit for database migrations and schema management
- **Development**: In-memory storage fallback for development without database

## Development Tooling
- **Build System**: Vite for frontend, esbuild for backend bundling
- **TypeScript**: Strict type checking with path mapping for clean imports
- **Code Quality**: PostCSS with Autoprefixer for CSS processing
- **Development Features**: Runtime error overlay and Replit integration for cloud development

# External Dependencies

## Core Frameworks
- **React**: UI framework with hooks and context
- **Express.js**: Backend web framework
- **Vite**: Frontend build tool and development server

## Database & ORM
- **Neon Database**: Serverless PostgreSQL hosting
- **Drizzle ORM**: Type-safe database toolkit
- **Drizzle Kit**: Migration and schema management

## UI & Styling
- **Tailwind CSS**: Utility-first CSS framework
- **Radix UI**: Headless component primitives
- **Framer Motion**: Animation library
- **Lucide React**: Icon library

## State Management
- **TanStack Query**: Server state management and caching
- **React Hook Form**: Form state management with validation

## Development Tools
- **TypeScript**: Static typing
- **ESBuild**: Fast JavaScript bundler
- **TSX**: TypeScript execution for development
- **Wouter**: Lightweight routing library

## Third-party Services
- **Replit**: Cloud development environment integration
- **Google Fonts**: Web font loading (Inter, JetBrains Mono, Architects Daughter)