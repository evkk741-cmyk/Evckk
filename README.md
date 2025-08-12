# AEGIS OS - 

## Project Overview

AEGIS OS is a modern desktop environment powered by the Google Gemini AI, featuring a sleek, high-end user interface. This project showcases the integration of powerful AI functionalities into a fluid and visually stunning desktop experience.

## ✨ Visual Synthesis Protocol: Activated

This version introduces a complete aesthetic transformation, shifting to a low-key, luxurious holographic interface.

1.  **New Aesthetic**: The UI has been redesigned with a sophisticated, dark "holographic" theme. It now features a deep blue/black palette with glowing cyan and glass-like accents. UI elements feature sharp lines, glowing highlights, and subtle animations to create an immersive, futuristic experience.
2.  **Immersive Background**: The previous background has been replaced with a high-quality, abstract data visualization background that evokes neural pathways, enhancing the theme while significantly improving performance.
3.  **Futuristic Typography**: The system-wide font has been changed to `IBM Plex Mono` to improve readability and reinforce the futuristic, code-centric aesthetic, ensuring information is conveyed clearly and efficiently.
4.  **Performance Optimization**: By replacing the resource-intensive wallpaper and streamlining styles, the entire OS is now faster and more responsive.

## ⚙️ Ultimate Refactoring & Optimization

This version introduces deep, structural improvements that elevate the project's quality, making it faster, more reliable, and easier to maintain.

1.  **AEGIS Sidebar Integration**: The persistent AEGIS chat window has been re-architected into a sleek, collapsible sidebar on the left. This provides a more elegant, integrated user experience and resolves the spatial conflict of a floating window. The main OS layout intelligently adapts when the sidebar is toggled.
2.  **Centralized State Management**: Implemented a professional state management pattern using Zustand, replacing scattered global variables with a single, reliable source of truth. This makes the application's state predictable, easier to debug, and highly scalable.
3.  **Dynamic Component Architecture**: The UI is no longer static. Windows and other elements are now dynamically created as "components" when needed and their lifecycle is tied to the central state, improving performance, memory usage, and maintainability.
4.  **Centralized App Registry**: A professional design pattern consolidates all application configurations (titles, icons, initialization functions) into a single, manageable `apps` registry. This eliminates redundant code, simplifies app launching, and makes the system far easier to extend.

## Project Features

### 🖥️ Desktop Environment
- A sleek, dark, holographic interface with glowing neon accents.
- Draggable and resizable windows with smooth animations.
- A floating, futuristic app dock.
- A customizable wallpaper system with a new abstract default.
- Right-click context menus for desktop and application actions.

### 🤖 AI-Powered Applications
- **AEGIS Core (Sidebar)**: A direct line to the advanced Gemini AI, seamlessly integrated into the OS as a collapsible left-hand sidebar.
- **AI Code Editor**: Generates HTML, CSS, and JS code from natural language descriptions.
- **Language Optimizer**: Refines and improves any text you provide, with selectable tones.
- **Image Generator**: Creates stunning images from text prompts.
- **Web Browser**: An AI-powered search browser.
- **Media Player**: Plays YouTube videos directly within the OS.

### ⌨️ System Functionality
- **File Manager**: A simulated interface for browsing files.
- **Window State Memory**: Remembers the position and size of your app windows.
- **System Tray & Notifications**: A modern, non-intrusive notification system.

## Quick Start

### 1. API Key Configuration
This system is designed to run in an environment where the `process.env.API_KEY` environment variable is pre-configured. You **do not** need to, and **should not**, set the API key manually in the code.

### 2. Launching the System
Simply open the `index.html` file in a modern web browser.

## Tech Stack

- **Language**: TypeScript
- **State Management**: Zustand
- **AI SDK**: Google GenAI SDK (`@google/genai`)
- **Styling**: Modern CSS3 (Variables, Flexbox, Grid)
- **Build Tool**: TypeScript Compiler (for development)

## System Requirements

- A modern browser (latest Chrome, Firefox, Edge, or Safari).
- A pre-configured `process.env.API_KEY` in the execution environment.
- A stable internet connection for AI features.

## License

MIT License
