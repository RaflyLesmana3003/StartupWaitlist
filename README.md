# Startup Waitlist Landing Page

A modern, responsive landing page built with React that allows users to join a waitlist for your startup. The page features a clean design, animations, and a simple form to collect user information.

## Features

- 🎨 Modern and professional design with animations
- 📝 Waitlist form with validation
- 📊 Real-time waitlist count display
- 💫 Smooth transitions and effects using Framer Motion
- 📱 Fully responsive design (mobile, tablet, desktop)
- ✨ Built with modern React and TypeScript

## Tech Stack

- **Frontend:**
  - React 18 with TypeScript
  - Tailwind CSS for styling
  - Shadcn UI components
  - React Hook Form for form management
  - Zod for validation
  - Framer Motion for animations
  - TanStack Query for data fetching

- **Backend:**
  - Express.js server
  - In-memory storage (can be easily switched to PostgreSQL)
  - Zod for API validation

## Development

### Prerequisites

- Node.js 20 or higher
- npm (comes with Node.js)

### Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
├── client/                # Frontend React application
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── hooks/        # Custom React hooks
│   │   ├── lib/          # Utility functions and setup
│   │   └── pages/        # Page components
├── server/               # Backend Express application
│   ├── routes.ts        # API routes
│   └── storage.ts       # Data storage implementation
└── shared/              # Shared code between frontend and backend
    └── schema.ts        # Data models and validation
```

## Contributing

1. Create a feature branch from `main`
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## License

MIT
