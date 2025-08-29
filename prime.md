# Amazon Clone - E-commerce Platform

## Overview

This is a modern e-commerce platform built as an Amazon clone, featuring a comprehensive product catalog with multiple categories including women's fashion, men's fashion, kids' items, electronics, home goods, and jewelry. The application provides a full shopping experience with product browsing, search functionality, detailed product pages, shopping cart management, and order processing.

The platform showcases contemporary web development practices with a React-based frontend and Express.js backend, implementing a clean separation of concerns through a monorepo structure with shared schemas and types.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript using Vite as the build tool
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: Zustand with persistence middleware for cart management
- **UI Framework**: Tailwind CSS with shadcn/ui component library
- **Design System**: Radix UI primitives with custom theming and CSS variables
- **Data Fetching**: TanStack Query (React Query) for server state management

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **Data Storage**: In-memory storage implementation with interface for future database integration
- **API Design**: RESTful endpoints following conventional patterns
- **Development Setup**: Hot reload with Vite middleware integration

### Database & Schema Design
- **ORM**: Drizzle ORM configured for PostgreSQL
- **Schema Management**: Centralized schema definitions in shared directory
- **Database Provider**: Neon Database serverless PostgreSQL
- **Migration Strategy**: Drizzle Kit for schema migrations and management

### Development & Deployment
- **Build System**: Vite for frontend, esbuild for backend bundling
- **Development Environment**: Integrated development with Vite middleware
- **Type Safety**: Full TypeScript coverage with strict compiler settings
- **Code Organization**: Monorepo structure with path aliases for clean imports

### Key Features
- **Product Catalog**: Multi-category product system with search and filtering
- **Shopping Cart**: Persistent cart with local storage synchronization
- **User Interface**: Responsive design with mobile-first approach
- **Search Functionality**: Real-time product search across categories
- **Product Management**: Featured products, ratings, reviews, and inventory tracking

## External Dependencies

### Core Framework Dependencies
- **@vitejs/plugin-react**: React plugin for Vite build system
- **express**: Web application framework for Node.js
- **wouter**: Minimalist routing library for React applications

### Database & ORM
- **drizzle-orm**: TypeScript ORM with SQL-like query builder
- **drizzle-kit**: Schema management and migration tools
- **@neondatabase/serverless**: Serverless PostgreSQL client for Neon Database

### UI & Styling
- **tailwindcss**: Utility-first CSS framework
- **@radix-ui/react-***: Accessible UI component primitives
- **class-variance-authority**: Utility for managing component variants
- **clsx**: Utility for constructing className strings conditionally

### Data Management
- **@tanstack/react-query**: Powerful data synchronization for React
- **zustand**: Small, fast, and scalable state management
- **zod**: TypeScript-first schema declaration and validation library

### Development Tools
- **typescript**: Static type checking for JavaScript
- **vite**: Fast build tool and development server
- **esbuild**: Extremely fast JavaScript bundler
- **tsx**: TypeScript execution environment for Node.js

### Additional Utilities
- **date-fns**: Modern JavaScript date utility library
- **nanoid**: URL-friendly unique string ID generator
- **react-hook-form**: Performant forms with easy validation
- **embla-carousel-react**: Lightweight carousel library for React