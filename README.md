# Page Prism - Intuit Front End A4A

## Project Overview

Page Prism is a web application designed to help designers and developers collect and organize visual inspirations for their projects.

## Key Features

- Create and manage design inspiration projects
- Capture screenshots of websites and save them as inspirations
- Organize inspirations within projects
- View and edit project and inspiration details

## Technology Stack

- React 18
- TypeScript
- Vite
- CSS Modules
- React Router
- IndexedDB (via idb library)

## Prerequisites

Before you begin, ensure you have the following installed on your development machine:

1. **Node.js** (version 18.20.2)
   - Download and install from [nodejs.org](https://nodejs.org/)
   - Verify installation: `node --version`

2. **npm** (usually comes with Node.js)
   - Verify installation: `npm --version`

3. **Git**
   - Download and install from [git-scm.com](https://git-scm.com/)
   - Verify installation: `git --version`

## Getting Started

1. Fork the repository:
   - Visit the GitHub repository
   - Click the "Fork" button in the top-right corner to create your own copy of the repository

2. Clone your forked repository:
   ```
   git clone https://github.com/your-username/page-prism.git
   cd page-prism
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and visit `http://localhost:5173` to view the application.

6. Run tests:
   ```
   npm test
   ```

   This will run all the tests in the project using Jest.

7. Run tests in watch mode (for development):
   ```
   npm test -- --watch
   ```

   This will run Jest in watch mode, which will re-run tests when files change.

## Project Structure

- `/src`: Source code
  - `/components`: Reusable React components
  - `/layouts`: Layout components
  - `/pages`: Page components
  - `/services`: API and data services
  - `/utils`: Utility functions
  - `/models`: TypeScript interfaces and types
  - `/hooks`: Custom React hooks

## Some Potential Tasks

1. Implement new features or enhance existing ones
2. Refactor and optimize existing code
3. Write unit tests for components and utilities
4. Improve the user interface and experience
5. Handle edge cases and error states
6. Demonstrate best practices in React and javascript development

## Evaluation Criteria

- Code quality and organization
- Component design and reusability
- State management
- Performance optimization
- UI/UX considerations
- Testing approach
- Problem-solving skills
- Attention to detail

## Additional Notes

- The project uses IndexedDB for local storage, simulating a backend database
- API calls can be mocked with artificial latency to simulate network requests

## Additional Setup

- **VS Code Extensions** (optional but recommended):
  - ESLint
  - Prettier

- **Environment Setup**:
  - This project uses Node.js version 18.20.2. To ensure you're using the correct version, you can use a version manager like `nvm` (Node Version Manager):
    ```
    nvm use
    ```
  - If you don't have `nvm` installed, you can get it from [here](https://github.com/nvm-sh/nvm).

- **Editor Configuration**:
  - The project includes a `.prettierrc` file for consistent code formatting. Make sure your editor is set up to use Prettier for formatting.

