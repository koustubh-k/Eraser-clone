# Eraser.io Clone

A full-stack clone of [Eraser.io](https://eraser.io/), a collaborative whiteboard and document editor designed for teams to brainstorm, plan, and create together in real-time. This project replicates the core features of Eraser.io, allowing users to create files with integrated text editing and drawing capabilities.

## 🚀 Live Demo

Check out the live application: [https://eraser-clone-eta.vercel.app/](https://eraser-clone-eta.vercel.app/)

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **User Authentication**: Secure login and registration using Kinde Authentication
- **Team Management**: Create and manage teams for collaborative work
- **File Creation**: Easily create new files with unique names
- **Collaborative Editing**:
  - **Text Editor**: Rich text editing powered by EditorJS with support for headers, lists, links, checklists, and images
  - **Whiteboard**: Interactive drawing and sketching using Excalidraw
- **Real-time Collaboration**: Work together with team members on documents and whiteboards
- **Responsive Design**: Modern, dark-themed UI built with Tailwind CSS and Shadcn/UI components
- **File Management**: Organize files by teams, with options to archive and track usage
- **Progress Tracking**: Monitor file usage with progress bars and upgrade prompts

## 🛠 Tech Stack

### Frontend

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/UI** - Modern UI components built on Radix UI
- **Lucide React** - Icon library
- **React Resizable Panels** - Adjustable layout components

### Backend & Database

- **Convex** - Real-time database and backend-as-a-service
- **Kinde Authentication** - User authentication and authorization

### Editors

- **EditorJS** - Block-style text editor
- **Excalidraw** - Virtual whiteboard for sketching

### Development Tools

- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

- **Node.js** (version 18 or higher)
- **npm**, **yarn**, **pnpm**, or **bun** package manager
- **Git** for version control

## 🚀 Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kaifcoder/eraser_clone.git
   cd eraser_clone
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root directory.
4. **Set up Convex:**

   - Install Convex CLI: `npm install -g convex`
   - Initialize Convex: `npx convex dev`
   - Follow the prompts to set up your Convex project

5. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

6. **Open your browser:**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 📖 Usage

1. **Sign Up/Login:** Create an account or log in using Kinde Authentication
2. **Create a Team:** Set up a team for collaboration
3. **Create Files:** Use the "New File" button in the sidebar to create documents
4. **Edit Content:**
   - Use the text editor for writing and formatting content
   - Switch to the whiteboard for drawing and diagramming
5. **Collaborate:** Share files with team members for real-time editing
6. **Manage Files:** View and organize your files in the sidebar

## 📁 Project Structure

```
eraser_clone/
├── app/                    # Next.js app directory
│   ├── _components/        # Custom React components
│   ├── _context/           # React context providers
│   ├── api/                # API routes
│   └── (routes)/           # Route groups
├── components/             # Reusable UI components
│   └── ui/                 # Shadcn/UI components
├── convex/                 # Convex backend functions
├── lib/                    # Utility functions
├── public/                 # Static assets
└── ...config files
```

For a detailed file-by-file description, see [file_descriptions.txt](./file_descriptions.txt) and [project_structure.txt](./project_structure.txt).

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Eraser.io](https://eraser.io/) for the inspiration
- [Next.js](https://nextjs.org/) for the amazing React framework
- [Convex](https://www.convex.dev/) for the real-time database
- [Kinde](https://kinde.com/) for authentication
- [Excalidraw](https://excalidraw.com/) for the whiteboard functionality
- [EditorJS](https://editorjs.io/) for the text editor

---

Built using Next.js, Convex, and modern web technologies.
