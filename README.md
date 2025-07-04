# 🚀 Scrumpty - Modern Task Management for Growing Teams

<div align="center">


<img src="public/Logo.png" alt="Scrumpty Logo" width="120" height="120" />

**Simplifying Task Management for Growing Teams**

[![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-000000?style=flat&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Appwrite](https://img.shields.io/badge/Appwrite-FD366E?style=flat&logo=appwrite&logoColor=white)](https://appwrite.io/)

*Empower your team with tools that simplify task management, improve coordination, and ensure nothing slips through the cracks as your business expands.*

[🌐 Live Demo](#) | [📖 Documentation](#) | [🐛 Report Bug](https://github.com/yourusername/scrumpty/issues)

</div>

---

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <h3>📋 Task Management</h3>
        <p>Create, assign, and track tasks with powerful workflows and custom fields</p>
      </td>
      <td align="center" width="33%">
        <h3>👥 Team Collaboration</h3>
        <p>Work together seamlessly with real-time updates and team workspaces</p>
      </td>
      <td align="center" width="33%">
        <h3>📊 Analytics</h3>
        <p>Get insights into team performance and project progress with detailed reports</p>
      </td>
    </tr>
    <tr>
      <td align="center" width="33%">
        <h3>📅 Timeline Views</h3>
        <p>Visualize project timelines with calendar views and Gantt charts</p>
      </td>
      <td align="center" width="33%">
        <h3>🔒 Security</h3>
        <p>Enterprise-grade security with role-based access control</p>
      </td>
      <td align="center" width="33%">
        <h3>⚡ Automation</h3>
        <p>Automate repetitive tasks and workflows to save time</p>
      </td>
    </tr>
  </table>
</div>

## 🛠️ Tech Stack

**Frontend:**
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Unstyled, accessible UI components
- **Lucide React** - Beautiful icon library
- **React Hook Form** - Performant forms with validation
- **Zod** - Schema validation
- **TanStack Query** - Data fetching and caching

**Backend & Database:**
- **Appwrite** - Backend-as-a-Service platform
- **Hono** - Lightweight web framework for API routes
- **Server Actions** - Next.js server-side functions

**UI/UX:**
- **shadcn/ui** - Re-usable component library
- **Sonner** - Toast notifications
- **React Big Calendar** - Calendar component
- **Recharts** - Chart library
- **Next Themes** - Theme switching

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18+ and **npm** (or **Bun** for faster package management)
- **Appwrite** account and project setup

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/scrumpty.git
   cd scrumpty
   ```

2. **Install dependencies**
   ```bash
   # Using npm
   npm install
   
   # Or using Bun (recommended)
   bun install
   ```

3. **Environment Setup**
   
   Create a `.env.local` file in the root directory:
   ```env
   # App Configuration
   NEXT_PUBLIC_APP_URL=http://localhost:3000
   
   # Appwrite Configuration
   NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
   NEXT_PUBLIC_APPWRITE_PROJECT=your_project_id
   NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
   NEXT_PUBLIC_APPWRITE_WORKSPACES_ID=your_workspaces_collection_id
   NEXT_PUBLIC_APPWRITE_MEMBERS_ID=your_members_collection_id
   NEXT_PUBLIC_APPWRITE_PROJECTS_ID=your_projects_collection_id
   NEXT_PUBLIC_APPWRITE_TASKS_ID=your_tasks_collection_id
   NEXT_PUBLIC_APPWRITE_IMAGES_BUCKET_ID=your_images_bucket_id
   
   # Server Key
   NEXT_APPWRITE_KEY=your_appwrite_server_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   bun dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:3000` to see the application in action!

## 📁 Project Structure

```
scrumpty/
├── public/                 # Static assets
│   ├── Logo.png           # App logo
│   ├── heroimg.jpg        # Landing page hero image
│   └── grid-dots.svg      # Background pattern
├── src/
│   ├── app/               # Next.js App Router
│   │   ├── (auth)/        # Authentication pages
│   │   ├── (dashboard)/   # Main dashboard routes
│   │   ├── (standalone)/  # Standalone pages
│   │   └── api/           # API routes
│   ├── components/        # Reusable UI components
│   │   ├── ui/            # shadcn/ui components
│   │   └── landing/       # Landing page components
│   ├── features/          # Feature-based modules
│   │   ├── auth/          # Authentication
│   │   ├── workspaces/    # Workspace management
│   │   ├── projects/      # Project management
│   │   ├── tasks/         # Task management
│   │   ├── members/       # Team member management
│   │   └── github/        # GitHub integration
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility libraries
│   └── config.ts          # Configuration constants
├── components.json        # shadcn/ui configuration
├── tailwind.config.ts     # Tailwind CSS configuration
└── next.config.mjs        # Next.js configuration
```

## 🎯 Core Features

### 🏢 Workspace Management
- Create and manage multiple workspaces
- Invite team members with role-based permissions
- Workspace analytics and insights
- Custom workspace branding

### 📊 Project Organization
- Create and organize projects within workspaces
- Project-specific analytics
- Custom project avatars and branding
- Project timeline visualization

### ✅ Task Management
- Create, edit, and delete tasks
- Assign tasks to team members
- Set due dates and priorities
- Drag-and-drop task reordering
- Bulk task operations
- Task status tracking (Todo, In Progress, Under Review, Completed)

### 👥 Team Collaboration
- User authentication and authorization
- Role-based access control (Admin, Member)
- Real-time updates
- Team member management
- Activity tracking

### 📈 Analytics & Reporting
- Workspace performance metrics
- Project progress tracking
- Task completion analytics
- Team productivity insights
- Visual charts and graphs

## 🎨 UI/UX Features

### 🌟 Modern Design
- Clean, professional interface
- Responsive design for all devices
- Dark/light theme support
- Smooth animations and transitions
- Accessible components

### 🎪 Landing Page
- Hero section with compelling CTAs
- Feature showcase
- Pricing tiers
- Professional footer
- SEO optimized

### 📱 Responsive Layout
- Mobile-first design approach
- Tablet and desktop optimizations
- Touch-friendly interactions
- Adaptive navigation

## 🔧 Development

### Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint

# Using Bun (faster alternative)
bun dev             # Start development server
bun run build       # Build for production
bun start           # Start production server
```

### Code Quality

- **TypeScript** for type safety
- **ESLint** for code linting
- **Prettier** formatting (via ESLint config)
- Component-based architecture
- Custom hooks for reusable logic
- Server-side validation with Zod

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables
4. Deploy automatically on every push

### Manual Deployment

```bash
# Build the application
npm run build

# Start the production server
npm run start
```

## 🔒 Environment Variables

Make sure to set up all required environment variables for production:

- `NEXT_PUBLIC_APP_URL` - Your production URL
- `NEXT_PUBLIC_APPWRITE_*` - Appwrite configuration
- `NEXT_APPWRITE_KEY` - Server-side Appwrite key

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Follow TypeScript best practices
- Use existing UI components when possible
- Write meaningful commit messages
- Test your changes thoroughly
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Vercel** for Next.js and hosting platform
- **Appwrite** for backend infrastructure
- **Radix UI** for accessible components
- **shadcn/ui** for the component library
- **Tailwind CSS** for styling utilities


<div align="center">

**Built with ❤️ by the Scrumpty Team**

[⭐ Star us on GitHub](https://github.com/yourusername/scrumpty)

</div>
