# Task Tracker

A modern, feature-rich task management application built with React, TypeScript, and Tailwind CSS.

## Features

- **Task Management** - Create, edit, delete, and mark tasks as complete
- **Priority Levels** - Assign low, medium, or high priority to tasks
- **Categories & Tags** - Organize tasks with custom categories and tags
- **Due Dates** - Set due dates with visual overdue indicators
- **Search & Filter** - Find tasks by keyword, category, priority, or tags
- **Dark Mode** - Toggle between light and dark themes
- **Persistent Storage** - Tasks saved to localStorage automatically
- **Responsive Design** - Works on desktop and mobile devices

## Tech Stack

- **React 18** with TypeScript
- **Vite** for fast development and builds
- **Tailwind CSS** with custom design tokens
- **shadcn/ui** component library
- **React Router** for navigation
- **TanStack Query** for data management
- **date-fns** for date formatting

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
git clone https://github.com/avishkar-004/Task.git
cd Task
npm install
```

### Development

```bash
npm run dev
```

The app runs at `http://localhost:8080`.

### Build

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── ui/              # Reusable UI components (shadcn)
│   ├── Login.tsx        # User authentication
│   ├── TaskDashboard.tsx # Main dashboard layout
│   ├── TaskForm.tsx     # Task creation/editing form
│   ├── TaskFilter.tsx   # Filter tabs (All/Pending/Complete)
│   ├── TaskItem.tsx     # Individual task card
│   ├── TaskList.tsx     # Task list container
│   └── TaskSearch.tsx   # Search and advanced filters
├── contexts/
│   └── ThemeContext.tsx  # Dark mode context provider
├── hooks/
│   ├── use-mobile.tsx   # Mobile detection hook
│   └── use-toast.ts     # Toast notification hook
├── lib/
│   └── utils.ts         # Utility functions
├── pages/
│   ├── Index.tsx        # Main page
│   └── NotFound.tsx     # 404 page
├── types/
│   └── task.ts          # TypeScript type definitions
└── utils/
    └── localStorage.ts  # Persistence layer
```

## License

MIT
