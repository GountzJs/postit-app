# Post-it App

Welcome to the Post-it App! This is a personal platform for organizing notes, thoughts, tools, and ideas using a "post-it" metaphor.

## Project Goal

The main goal is to create a simple and intuitive tool to manage information across different areas of interest without creating a chaotic mess. To achieve this, the application is built around the concept of **workspaces**. Each workspace (e.g., "Frontend," "Design," "Game Dev") acts as a separate container for your post-it notes, allowing you to keep your thoughts neatly organized and context-specific.

## Tech Stack

*   **Framework:** [Nuxt.js](https://nuxt.com/)
*   **UI Library:** [Vue.js](https://vuejs.org/)
*   **Package Manager:** [Bun](https://bun.sh/)

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

First, ensure you have [Bun](https://bun.sh/) installed.

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd postit-app
    ```
3.  Install the dependencies:
    ```bash
    bun install
    ```

### Running the Development Server

Start the development server on `http://localhost:3000`:

```bash
bun run dev
```

The app will automatically reload if you change any of the source files.

## Future Direction

The project is currently in its initial development phase. The roadmap includes:

*   Building the core functionality for creating, editing, and deleting post-its.
*   Implementing the workspace system to organize post-its.
*   Designing a clean, intuitive, and visually appealing user interface that resembles a real-world post-it board.
*   Adding features like drag-and-drop for post-its.
*   Persisting data locally in the browser.