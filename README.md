# 🚀 Sisques Labs Landing Page

Modern, high-performance landing page for Sisques Labs, built with Next.js 16 and TypeScript. Features internationalization, dark mode, smooth animations, and a responsive design.

## ✨ Features

- 🌐 **Internationalization** - Multi-language support (English & Spanish) using `next-intl`
- 🎨 **Dark Mode** - Theme switching with `next-themes`
- ✨ **Smooth Animations** - Powered by Motion (Framer Motion)
- 📱 **Responsive Design** - Mobile-first approach with Tailwind CSS
- ⚡ **Performance Optimized** - Built with Next.js 16 App Router
- 🎯 **SEO Ready** - Optimized for search engines
- 🧩 **Component Architecture** - Organized by feature with reusable components

## 🛠️ Tech Stack

- **Framework**: [Next.js 16.0.3](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/)
- **Animations**: [Motion](https://motion.dev/) (Framer Motion)
- **Internationalization**: [next-intl](https://next-intl-docs.vercel.app/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **3D Globe**: [Cobe](https://github.com/shuding/cobe)

## 📋 Prerequisites

- Node.js 20.x or higher
- pnpm (recommended), npm, yarn, or bun

## 🚀 Getting Started

### Installation

```bash
# Install dependencies
pnpm install
```

### Development

```bash
# Run the development server
pnpm dev

# or
npm run dev
# or
yarn dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Building

```bash
# Build for production
pnpm build

# Start production server
pnpm start
```

### Linting

```bash
# Run ESLint
pnpm lint
```

## 📁 Project Structure

```
.
├── app/                    # Next.js App Router
│   ├── [locale]/          # Internationalized routes
│   └── layout.tsx         # Root layout
├── components/            # Shared UI components
│   ├── ui/               # Reusable UI primitives
│   └── providers/        # Context providers
├── src/                  # Feature-based modules
│   ├── contact/         # Contact section
│   ├── hero/           # Hero section
│   ├── portfolio/      # Portfolio section
│   ├── services/       # Services section
│   ├── shared/         # Shared utilities & components
│   ├── technologies/   # Technologies section
│   ├── testimonials/   # Testimonials section
│   └── work-process/   # Work process section
├── public/             # Static assets
└── profile/           # Organization profile README
```

## 🌍 Internationalization

The project supports multiple languages through `next-intl`. Currently available languages:

- English (`en`)
- Spanish (`es`)

Language files are located in `src/shared/locales/`.

## 🎨 Theming

Dark mode is supported and can be toggled via the theme toggle component. The theme preference is persisted in localStorage.

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory if needed:

```env
# Add your environment variables here
```

### Tailwind CSS

The project uses Tailwind CSS 4 with custom configuration. Theme colors and styles can be customized in `tailwind.config.ts`.

## 🚢 Deployment

The project is configured with GitHub Actions for CI/CD. Builds are automatically triggered on pushes to `main` and `dev` branches.

### Deploy on Vercel

The easiest way to deploy is using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/sisques-labs/landing)

## 📝 Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint

## 🤝 Contributing

This is a private repository for Sisques Labs. For questions or issues, please contact the development team.

## 📄 License

Private - All rights reserved © 2024 Sisques Labs

## 📬 Contact

- **Email**: contact@sisqueslabs.com
- **Website**: [Sisques Labs](https://sisqueslabs.com)

---

Built with ❤️ by [Sisques Labs](https://github.com/sisques-labs)
