# RetroFlow - Frontend

RetroFlow is a collaborative Agile Sprint & Retrospective management platform. This repository contains the Next.js 16 frontend application.

## 🚀 Tech Stack

- **Framework**: [Next.js 16 (App Router)](https://nextjs.org/)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Real-time Sync**: Socket.io Client
- **Authentication**: Firebase Auth & Custom JWT

## 📁 Project Structure

```
├── public/                 # Static assets & icons
├── src/
│   ├── app/                # Next.js App Router pages & layouts
│   │   ├── (auth)/         # Login, Signup, Forgot Password, Verify Email
│   │   ├── dashboard/      # Main dashboard & project views
│   │   ├── projects/       # Project backlog, sprint management, settings
│   │   └── retro/          # Real-time interactive retrospective board
│   ├── components/         # Reusable UI & domain-specific components
│   ├── hooks/              # Custom React hooks (socket, permissions, state)
│   ├── lib/                # Socket, Firebase, API, and date utilities
│   ├── services/           # REST API client services
│   └── types/              # TypeScript definitions & models
└── package.json
```

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+ or 20+
- Running instance of RetroFlow Backend

### Installation

1. Clone the repository:
```bash
git clone https://github.com/gopalgohil/RetroFlow_Frontend.git
cd RetroFlow_Frontend
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
Copy `.env.example` to `.env.local` and set your backend API and socket URLs:
```bash
cp .env.example .env.local
```

4. Start development server:
```bash
npm run dev
```

The app will be running at [http://localhost:3000](http://localhost:3000).

## 📦 Scripts

- `npm run dev`: Starts development server
- `npm run build`: Builds the production bundle
- `npm run start`: Runs production build
- `npm run lint`: Runs ESLint checks
