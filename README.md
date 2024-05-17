
---

### Repository Name: `vite-express-single-port-boilerplate`

### Description:

This repository serves as a boilerplate for building full-stack applications with a Vite + React + TypeScript frontend and an Express + TypeScript backend. The key feature of this setup is that both the frontend and backend are served from the same port in production, providing a seamless development and deployment experience.

### Features:

- **Vite + React + TypeScript Frontend**:
  - Fast development server with hot module replacement (HMR).
  - Modern JavaScript and TypeScript support.
  - Easy setup for React applications.

- **Express + TypeScript Backend**:
  - Lightweight and efficient server for handling API requests.
  - TypeScript for type-safe backend code.
  - Simple integration with frontend for API calls.

- **Single-Port Production Setup**:
  - Frontend and backend served from the same port.
  - Efficient and unified deployment process.

### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/TheodoreRed/vite-express-single-port-boilerplate.git
   cd vite-express-single-port-boilerplate
   ```

2. **Install dependencies**:
   ```bash
   npm install
   cd app && npm install
   cd ../server && npm install
   ```

3. **Run in development mode**:
   ```bash
   npm run dev
   ```
   - Open your browser and navigate to `http://localhost:5173`.

4. **Build for production**:
   ```bash
   npm run build
   ```

5. **Serve in production mode**:
   ```bash
   npm run serve
   ```
   - Open your browser and navigate to `http://localhost:5000`.

### Directory Structure

```
my-project/
├── app/                  # Frontend (Vite + React + TypeScript)
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── routes/
│   │       ├── Home.tsx
│   │       └── About.tsx
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   ├── package.json
│   ├── vite.config.ts
├── server/               # Backend (Express + TypeScript)
│   ├── node_modules/
│   ├── src/
│   │   └── index.ts
│   ├── dist/
│   ├── tsconfig.json
│   ├── package.json
├── node_modules/
├── package.json
```

---