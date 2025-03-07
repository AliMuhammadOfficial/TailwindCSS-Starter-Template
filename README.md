# TailwindCSS Starter Template

A lightweight starter template for building websites with TailwindCSS and Vite.

## What is TailwindCSS?

TailwindCSS is a utility-first CSS framework that lets you build designs directly in your HTML. Instead of writing custom CSS, you use predefined classes like `text-blue-500`, `p-4`, or `flex` to style your elements.

### Key Benefits

- **No more naming CSS classes**: Use Tailwind's predefined utility classes
- **Consistency**: Built-in design system for colors, spacing, and more
- **Responsive design**: Easily make your site work on different screen sizes with classes like `md:flex`
- **Customizable**: Extend or modify the default theme to match your design needs

## Getting Started

1. Clone this repository
   ```
   git clone git@github.com:AliMuhammadOfficial/TailwindCSS-Starter-Template.git
   cd TailwindCSS-Starter-Template
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:5173`

## Basic Usage

### Colors
```html
<p class="text-blue-500">Blue text</p>
<div class="bg-green-200">Green background</div>
```

### Spacing
```html
<div class="p-4">Padding on all sides</div>
<div class="m-2">Margin on all sides</div>
<div class="py-2 px-4">Padding: vertical 2, horizontal 4</div>
```

### Typography
```html
<h1 class="text-2xl font-bold">Large bold title</h1>
<p class="text-sm text-gray-500">Small gray text</p>
```

### Layout
```html
<div class="flex justify-between items-center">
  <div>Left item</div>
  <div>Right item</div>
</div>
```

### Responsive Design
```html
<div class="block md:flex lg:grid">
  <!-- Changes layout at different breakpoints -->
</div>
```

## Project Structure

- `index.html` - Main HTML file
- `src/style.css` - CSS file that imports Tailwind
- `vite.config.js` - Vite configuration
- `public/` - Static assets

## Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## Learn More

- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [Vite Documentation](https://vitejs.dev/guide/)