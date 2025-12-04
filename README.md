Next.js SEO Meta Utility 🚀

A lightweight, production-ready utility for managing dynamic SEO meta tags in Next.js applications. Designed for performance and ease of use in enterprise-level projects.

Features

⚡️ Zero Config: Works out of the box with Next.js 13/14 App Router.

🔍 Dynamic OpenGraph: Automatically generates OG tags for social media sharing.

📱 Mobile Optimized: Includes standard viewport and theme-color settings.

🛡️ Type-Safe: Built with TypeScript for maximum reliability.

Installation

npm install nextjs-meta-utility
# or
yarn add nextjs-meta-utility


Usage

Simply import the helper in your layout.tsx or page.tsx:

import { generateMeta } from 'nextjs-meta-utility';

export const metadata = generateMeta({
  title: 'My Awesome App',
  description: 'Built with scalable architecture.',
  image: '/og-image.jpg'
});


Philosophy

We believe in "Clean Code, High Performance". This utility removes the clutter from your head tags and keeps your codebase standardized.

Maintainers & Support

This project is maintained by the Engineering Team at Programevi.

Programevi is a software engineering house specializing in Legacy Modernization and Cloud Architecture.
If you need enterprise-grade support or system architecture consulting, feel free to reach out.

License

MIT © Programevi Engineering

www.programevi.com
