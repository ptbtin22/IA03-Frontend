# User Registration Frontend

React frontend application for user authentication with signup and login.

## Tech Stack

- React 19 + Vite
- React Router DOM (routing)
- React Hook Form (validation)
- React Query (API state)
- Zustand (global state)
- Axios (HTTP client)
- Tailwind CSS (styling)

## Quick Start

### 1. Install Dependencies

```bash
npm install
```

### 2. Environment Setup

Create `.env` file:

```env
VITE_API_URL=http://localhost:3000
```

For production, set to your backend URL:

```env
VITE_API_URL=https://your-backend.onrender.com
```

### 3. Run Application

```bash
# Development
npm run dev

# Production build
npm run build
npm run preview
```

App runs at `http://localhost:5173`

## Features

- User registration with email/password
- Login with mock authentication
- Form validation with React Hook Form
- API integration with React Query
- Persistent auth state with Zustand
- Responsive design with Tailwind CSS
- Loading states and error handling

## Pages

- **Home** (`/`) - Landing page with auth status
- **Signup** (`/signup`) - User registration form
- **Login** (`/login`) - Login form (mock auth)

## Project Structure

```
src/
├── pages/
│   ├── Home.jsx       # Landing page
│   ├── Login.jsx      # Login page
│   └── Signup.jsx     # Registration page
├── services/
│   └── api.js         # API client
├── store/
│   └── authStore.js   # Zustand auth store
├── App.jsx            # Routes
└── main.jsx           # Entry point
```

## Deployment

**Vercel (Recommended):**

1. Import GitHub repository
2. Set root directory: `frontend`
3. Framework: Vite
4. Add environment variable: `VITE_API_URL`
5. Deploy

**Live Demo:** https://ia03-frontend-three.vercel.app

## License

MIT
