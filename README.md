# 📞 Turing Technologies - Frontend Technical Test

This is a frontend web application built as a solution to the Turing Technologies frontend technical test. It displays a list of calls with pagination, filtering, call detail viewing, note-taking, and archiving functionalities.

## 🚀 Tech Stack

- **Next.js 14**
- **TypeScript**
- **GraphQL (Apollo Client)**
- **Material UI (MUI)**
- **Authentication Context**
- **Filtering + Pagination**

## 🔧 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/turingtech-frontend-test.git
cd turingtech-frontend-test

### 2.  Install dependencies
npm install

### 3.  Set up environment variables
NEXT_PUBLIC_API_URL=https://your-graphql-api.com/graphql

### 4. Running the App locally
npm run dev

### 5. Project Structure
.
├── components          # Reusable UI components (CallTable, Header, Modals, etc.)
├── context             # AuthContext for managing user auth state
├── features/calls      # GraphQL queries/mutations + hooks for call data
├── pages               # Next.js routing (e.g., login, homepage)
├── styles              # Global styles and MUI theme
├── types               # TypeScript types for calls and user
├── lib                 # Apollo client configuration
└── public              # Static assets (logo, etc.)

## Features
✅ Login page with mock authentication
✅ Calls table with:
    Pagination
    Archived/Unarchived filter
    Add Notes modal
✅ Call Details Page (/calls/[id])
✅ Toggle archive/unarchive status from Status Badge
✅ Responsive design with Material UI
✅ Client-side routing with next/navigation
✅ Auth-protected routes

## Testing
Testing has not been implemented yet but we can write unit and integration tests using:
    Jest
    React Testing Library
```
