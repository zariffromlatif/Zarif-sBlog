# Personal Blog

A modern personal blog built with Next.js, TypeScript, and Tailwind CSS.

## Features

- Clean and modern design
- Responsive layout
- TypeScript support
- Tailwind CSS for styling
- Markdown support for blog posts
- SEO optimized

## Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd personal-blog
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

```
src/
├── app/              # Next.js app directory
│   ├── about/       # About page
│   ├── posts/       # Blog posts
│   ├── layout.tsx   # Root layout
│   └── page.tsx     # Home page
├── components/      # React components
├── lib/            # Utility functions
└── styles/         # Global styles
```

## Customization

1. Update the content in `src/app/page.tsx` to add your blog posts
2. Modify the About page in `src/app/about/page.tsx`
3. Customize the styling in `src/app/globals.css`
4. Update the metadata in `src/app/layout.tsx`

## Deployment

The easiest way to deploy your blog is to use the [Vercel Platform](https://vercel.com/new).

## License

This project is open source and available under the [MIT License](LICENSE). 