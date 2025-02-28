# Team Jugaad Gadget Rental Platform

A modern web application for renting high-quality tech gadgets with a seamless user experience.

## Overview

Team Jugaad brings you an innovative rental solution - high-quality gadgets at a fraction of the cost, whenever you need them. This application allows users to browse available gadgets, learn about rental terms, and submit contact requests.

## Features

- **Product Catalog**: Browse a variety of tech gadgets available for rent
- **Rental Process Guide**: Simple 4-step rental process explanation
- **Contact Form**: Easy way for customers to get in touch
- **FAQ Section**: Common questions about rental terms and conditions
- **Coverage Areas**: Information about cities where service is available

## Tech Stack

### Frontend
- React with TypeScript
- TailwindCSS for styling
- Shadcn UI components
- Wouter for routing
- React Query for data fetching

### Backend
- Express.js with TypeScript
- In-memory storage (MemStorage implementation)
- RESTful API endpoints

## Project Structure

```
├── client               # Frontend React application
│   ├── src              # Source code
│   └── index.html       # Entry HTML file
├── server               # Express backend
│   ├── index.ts         # Server entry point
│   ├── routes.ts        # API route definitions
│   └── storage.ts       # Data storage implementation
├── shared               # Shared code between client and server
│   └── schema.ts        # Data schema definitions
```

## API Endpoints

- `GET /api/products`: Retrieves all available products
- `POST /api/contact`: Submits a contact message

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

Clone the repository and install dependencies:

```bash
npm install
```

### Running the Application

Start the development server:

```bash
npm run dev
```

This will start both the backend server and the frontend development server.

## Development

The application uses:
- TypeScript for type safety
- Drizzle ORM for database operations
- Zod for schema validation

## Deployment

The application is configured to be deployed on Replit.

## Theme Customization

The application uses a theme.json file for customizing appearance. The current theme is:
- Variant: Professional
- Primary color: hsl(214, 80%, 45%)
- Appearance: Light
- Border radius: 0.5


