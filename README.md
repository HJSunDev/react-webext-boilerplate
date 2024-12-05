# React WebExt Boilerplate

A modern boilerplate for creating browser extensions using React, WXT, and shadcn/ui.

## Features

- 🚀 Built with [WXT](https://wxt.dev/) for rapid development and hot reloading
- ⚛️ React 18 for efficient UI development
- 🎨 TailwindCSS for quick and responsive styling
- 🧰 [shadcn/ui](https://ui.shadcn.com/) for beautiful, accessible, and customizable UI components
- 📦 TypeScript support for enhanced developer experience
- 🔧 Pre-configured with essential tools and best practices

## Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

## Getting Started

1. Install dependencies:

   ```
   npm install
   ```
2. Start the development server:

   ```
   npm run dev
   ```
3. To build the extension:

   ```
   npm run build
   ```

## Scripts

- `npm run dev`: Start the development server with hot reloading
- `npm run dev:firefox`: Start the development server for Firefox
- `npm run build`: Build the extension for Chrome
- `npm run build:firefox`: Build the extension for Firefox
- `npm run zip`: Create a zip file of the built extension for Chrome
- `npm run zip:firefox`: Create a zip file of the built extension for Firefox
- `npm run compile`: Run TypeScript compiler without emitting files
- `npm run postinstall`: Prepare WXT after installation

## Key Dependencies

- [WXT](https://wxt.dev/): A powerful toolkit for building browser extensions with hot reloading support
- [React](https://reactjs.org/): A JavaScript library for building user interfaces
- [TailwindCSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development
- [shadcn/ui](https://ui.shadcn.com/): A collection of re-usable components built with Radix UI and Tailwind CSS
- [@webext-core/messaging](https://github.com/webext-core/messaging): Simplified messaging for browser extensions
- [TypeScript](https://www.typescriptlang.org/): Adds static typing to JavaScript for improved developer experience

## Development

This boilerplate uses WXT, which provides several powerful features:

- Hot Module Replacement (HMR) for rapid development
- TypeScript support out of the box
- Easy configuration with `wxt.config.ts` 
- Cross-browser compatibility (Chrome and Firefox)

To start development, run `npm run dev`. This will start the WXT development server with hot reloading enabled.

### Using shadcn/ui Components

This boilerplate comes pre-configured with shadcn/ui, allowing you to easily use and customize beautiful UI components. Here's a quick example of how to use a shadcn/ui component:

```jsx
import { Button } from "@/components/ui/button"

function MyComponent() {
  return (
    <Button variant="outline">Click me</Button>
  )
}
```

You can find more components and usage examples in the [shadcn/ui documentation](https://ui.shadcn.com/docs).

## Building for Production

To build the extension for production, use:

- For Chrome: `npm run build`
- For Firefox: `npm run build:firefox`

The built extension will be in the `dist` directory.

## License

This project is open source and available under the [MIT License](LICENSE).
