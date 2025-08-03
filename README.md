# 🚀 Next.js Dashboard - Full Stack Learning Journey

A modern dashboard application built with Next.js App Router as part of my full-stack development learning course.

![Dashboard Preview](public/hero-desktop.png)

## 📚 What I've Learned So Far

### 🎨 **Frontend Fundamentals**
- **Next.js App Router**: Implemented the new App Router architecture with proper file-based routing
- **React Components**: Created reusable components like `AcmeLogo` and responsive layouts
- **TypeScript Integration**: Full TypeScript setup for type safety and better development experience
- **Client Components**: Understanding `'use client'` directive for interactive components

### 🎯 **Styling & Design**
- **Tailwind CSS**: Responsive design with utility-first CSS framework
- **Custom Fonts**: Integrated Google Fonts (Inter & Lusitana) using Next.js font optimization
- **Responsive Images**: Implemented Next.js `Image` component for optimized loading
- **CSS Modules**: Understanding of component-scoped styling options
- **Dynamic Styling**: Using `clsx` library for conditional CSS classes

### 🧭 **Navigation & Routing**
- **Dynamic Navigation**: Built active link highlighting with `usePathname()` hook
- **Responsive Design**: Mobile-first navigation that adapts to different screen sizes
- **Icon Integration**: Heroicons for consistent UI iconography
- **Route Management**: File-based routing with dashboard subdirectories

### 🏗️ **Project Structure & Architecture**
```
app/
├── layout.tsx          # Root layout with global styles
├── page.tsx           # Landing page component
├── dashboard/         # Dashboard section (file-based routing)
├── ui/                # Reusable UI components
│   ├── fonts.ts       # Font configurations
│   ├── global.css     # Global styles
│   ├── acme-logo.tsx  # Logo component
│   └── dashboard/     # Dashboard-specific components
│       └── nav-links.tsx  # Navigation component
├── lib/               # Utility functions
│   └── placeholder-data.ts  # Mock data for development
├── query/             # Database queries
└── seed/              # Database seeding
```

### 🛠️ **Development Tools**
- **Package Management**: Using `pnpm` for efficient dependency management
- **Code Quality**: ESLint and TypeScript for code consistency
- **Build Optimization**: Next.js automatic optimization and bundling
- **State Management**: React hooks for component state

## 🌟 **Key Features Implemented**

✅ **Landing Page**
- Hero section with responsive images
- Modern gradient backgrounds
- Interactive navigation links
- Mobile-first responsive design

✅ **Component Architecture**
- Modular component structure
- Reusable UI elements
- TypeScript props and interfaces

✅ **Dashboard Navigation**
- Active link highlighting based on current route
- Responsive navigation with mobile/desktop variants
- Icon-based navigation with Heroicons
- Conditional styling with `clsx` utility

✅ **Performance Optimization**
- Next.js Image optimization
- Font optimization with `next/font`
- CSS-in-JS with Tailwind utilities
- Client-side routing for smooth navigation

## 🚧 **Next Steps in My Learning Journey**

- [ ] Dashboard layout and sidebar implementation
- [ ] Database integration and data fetching
- [ ] User authentication and authorization
- [ ] Dashboard functionality with charts and metrics
- [ ] API routes and server-side logic
- [ ] Deployment and production optimization

## 🛠️ **Tech Stack**

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS + clsx for conditional classes
- **Icons**: Heroicons
- **Fonts**: Google Fonts (Inter, Lusitana)
- **Package Manager**: pnpm
- **State Management**: React Hooks

## 🚀 **Getting Started**

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd nextjs-dashboard
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Run the development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📖 **Learning Resources**

This project follows the [Next.js Learn Course](https://nextjs.org/learn) curriculum, focusing on:
- Modern React patterns
- Full-stack development concepts
- Best practices for production applications

## 💡 **Key Learnings & Insights**

- **Template Literals**: Understanding when to use backticks vs quotes for dynamic className generation
- **Font Optimization**: How Next.js optimizes web fonts for better performance
- **Component Composition**: Building reusable, maintainable React components
- **File-based Routing**: Leveraging Next.js App Router for intuitive navigation structure
- **Conditional Styling**: Using `clsx` for dynamic CSS classes based on component state
- **Client vs Server Components**: Understanding when to use `'use client'` directive
- **React Hooks**: Implementing `usePathname()` for route-aware components
- **Responsive Design**: Creating mobile-first components that adapt to screen sizes

---

*This is a learning project - feedback and suggestions are always welcome! 🎓*