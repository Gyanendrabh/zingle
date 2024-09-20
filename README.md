# Group Chat Application

A real-time group chat application built with Next.js, TypeScript, Supabase, and Tailwind CSS. This application allows users to communicate in groups, with features for message editing, deletion, and email authentication.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)


## Features

- User authentication via email with verification.
- Real-time messaging using Supabase.
- Edit and delete messages.
- Responsive design with Tailwind CSS.

## Technologies

This project uses the following dependencies:

- *Next.js*: Framework for building server-side rendered React applications.
- *TypeScript*: Superset of JavaScript that adds static typing.
- *Supabase*: Backend-as-a-Service for authentication and real-time database features.
- *Tailwind CSS*: Utility-first CSS framework for styling.
- *ESLint*: Linter for identifying and fixing problems in JavaScript code.
- *PostCSS*: Tool for transforming CSS with JavaScript plugins.

## Getting Started

To get started with this Next.js project, follow these steps:

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v14.x or later)
- [npm](https://www.npmjs.com/get-npm) or [yarn](https://yarnpkg.com/getting-started/install)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

2. **Setup environment variables**

    ```NEXT_PUBLIC_SUPABASE_URL = <Your supabase url>
    NEXT_PUBLIC_SUPABASE_ANON_KEY = <Your supabase anon key>

3. **Install dependencies: If you're using npm:**

    ```bash
    npm i
    # or
    yarn add
    # or
    pnpm i

4. **Run the development servers**

    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    # or
    bun dev
