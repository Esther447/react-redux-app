# React + Redux + TypeScript

A React application demonstrating Redux state management without Redux Toolkit, built with Vite and TypeScript.

## Tech Stack

- React 19
- TypeScript
- Redux (manual setup)
- React-Redux
- Redux-Logger
- Vite

## Project Structure

```
src/
├── store/
│   ├── actions/
│   │   └── counterActions.ts   # Action types and action creators
│   ├── reducers/
│   │   ├── counterReducer.ts   # Counter reducer
│   │   └── index.ts            # Combined root reducer
│   └── store.ts                # Redux store with logger middleware
├── components/
│   ├── Counter.tsx             # Counter component using useSelector & useDispatch
│   └── Counter.module.css
├── App.tsx
└── main.tsx                    # Redux Provider setup
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open `http://localhost:5173/` in your browser.

## Features

- Global state management with Redux
- Increment, decrement, and reset counter actions
- Redux Logger middleware logs state changes to the browser console
- TypeScript types for state and dispatch
