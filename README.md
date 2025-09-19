# React Toast Demo

A beautiful toast notification system built with React, TypeScript, and Tailwind CSS.

## Features

- 🎨 Beautiful, modern design with smooth animations
- 🎯 TypeScript support with full type safety
- 🎨 Tailwind CSS styling
- 📱 Responsive design
- ⚡ Lightweight and performant
- 🎪 Multiple toast types (success, error, warning, info)
- ⏱️ Auto-dismiss with customizable duration
- 🎭 Smooth enter/exit animations with eye-catching icon effects

## Getting Started

1. **Install dependencies:**
```bash
npm install
```

2. **Start the development server:**
```bash
npm run dev
```

3. **Build for production:**
```bash
npm run build
```

## Usage

The demo shows how to use the toast system in your React applications:

```tsx
import { useToast } from './hooks/useToast';

function MyComponent() {
  const { toast } = useToast();

  const handleSuccess = () => {
    toast.success('Operation completed successfully!');
  };

  return (
    <button onClick={handleSuccess}>
      Show Success Toast
    </button>
  );
}
```

## Toast Types

- **Success**: Green themed with checkmark icon
- **Error**: Red themed with X icon  
- **Warning**: Yellow themed with triangle icon
- **Info**: Blue themed with info icon

## Customization

The toast system is built with Tailwind CSS and can be easily customized by modifying the component styles.

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide React (icons)# react-quick-notify-demo
