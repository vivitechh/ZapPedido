# ZapPedido - Food Delivery & POS System

## Overview

ZapPedido is a modern food delivery and point-of-sale system designed for restaurants and food establishments. The application provides a complete solution for managing orders, deliveries, and customer interactions through a responsive web interface with WhatsApp integration and PIX payment support.

The system is built as a full-stack application with a React frontend, Express.js backend, and PostgreSQL database, featuring a landing page that showcases the platform's capabilities and drives user adoption.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development practices
- **Styling**: Tailwind CSS with shadcn/ui component library for consistent, accessible UI components
- **Animations**: Framer Motion for smooth, engaging user interactions
- **State Management**: TanStack Query (React Query) for server state management and caching
- **Routing**: Wouter for lightweight client-side routing
- **Build Tool**: Vite for fast development and optimized production builds

### Backend Architecture
- **Runtime**: Node.js with Express.js framework for RESTful API development
- **Language**: TypeScript for type-safe server-side development
- **Database Layer**: Drizzle ORM with PostgreSQL for type-safe database operations
- **Session Management**: In-memory storage with extensible interface for future database integration
- **Development**: Hot reload with tsx for rapid development cycles

### Database Design
- **Primary Database**: PostgreSQL configured via Drizzle ORM
- **Schema Management**: Drizzle Kit for migrations and schema generation
- **Connection**: Neon serverless PostgreSQL for cloud deployment
- **Current Schema**: Basic user management with username/password authentication
- **Extensibility**: Modular schema design in shared directory for easy expansion

### Component System
- **Design System**: shadcn/ui components with New York style variant
- **Accessibility**: Radix UI primitives ensuring WCAG compliance
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
- **Icon System**: Lucide React for consistent iconography
- **Form Handling**: React Hook Form with Zod validation schemas

### Development Workflow
- **Monorepo Structure**: Shared types and schemas between client and server
- **Path Aliases**: Configured for clean imports (@/, @shared/, @assets/)
- **Hot Reload**: Both frontend and backend support development hot reload
- **Type Safety**: End-to-end TypeScript with shared schemas

## External Dependencies

### Core Infrastructure
- **Database**: Neon PostgreSQL serverless database
- **Database ORM**: Drizzle ORM with PostgreSQL adapter for type-safe queries
- **Session Store**: Connect-pg-simple for PostgreSQL session storage

### Frontend Libraries
- **UI Components**: Radix UI primitives for accessible component foundations
- **Animation**: Framer Motion for performance-optimized animations
- **Forms**: React Hook Form with Hookform Resolvers for validation integration
- **Date Handling**: date-fns for date manipulation and formatting
- **Charts**: Recharts integration via shadcn/ui chart components

### Development Tools
- **Bundling**: Vite with React plugin for fast development builds
- **TypeScript**: Full TypeScript support with strict mode enabled
- **CSS Processing**: PostCSS with Tailwind CSS and Autoprefixer
- **Code Quality**: ESBuild for production bundling

### Planned Integrations
- **Payment Processing**: PIX payment system integration (Brazil)
- **Messaging**: WhatsApp API for order notifications and customer communication
- **Maps**: Location services for delivery tracking and area management
- **Cloud Storage**: Asset management for menu images and branding materials