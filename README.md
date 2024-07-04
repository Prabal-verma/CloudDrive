
# CloudDrive

CloudDrive is a cloud storage web application built using Next.js and TypeScript. It leverages Clerk for authentication, Shadcn for the UI framework, and Convex for backend services.

![CloudDrive UI](path-to-your-image.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

CloudDrive is a robust and user-friendly cloud storage solution designed to securely store and manage your files. With a sleek UI and powerful backend, it provides an intuitive and efficient user experience.

## Features

- **Secure Authentication**: Integrated with Clerk for secure user authentication.
- **Responsive UI**: Built with Shadcn for a modern and responsive user interface.
- **Scalable Backend**: Powered by Convex for efficient and scalable backend services.
- **File Management**: Upload, download, and organize your files effortlessly.
- **Real-time Updates**: Real-time syncing of files and data.

## Tech Stack

- **Framework**: Next.js
- **Language**: TypeScript
- **Authentication**: Clerk
- **UI Framework**: Shadcn
- **Backend Service**: Convex

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm or yarn
- Convex account
- Clerk account

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Prabal-verma/CloudDrive.git
   cd clouddrive
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root of the project and add the following variables:

   ```env
   NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
   CLERK_API_KEY=<your-clerk-api-key>
   CONVEX_URL=<your-convex-url>
   ```

### Running the App

Start the development server:

```bash
npm run dev
# or
yarn dev
```

The app will be available at `http://localhost:3000`.

## Project Structure

```plaintext
.
├── public
│   └── images
│       └── ui.png
├── src
│   ├── components
│   ├── pages
│   │   ├── api
│   │   ├── _app.tsx
│   │   └── index.tsx
│   ├── styles
│   ├── utils
│   └── hooks
├── .env.local
├── next.config.js
├── package.json
├── tsconfig.json
└── README.md
```

## Usage

1. **Sign Up / Sign In**: Use Clerk for authentication.
2. **Upload Files**: Upload files to your CloudDrive storage.
3. **Manage Files**: Create folders, move files, and organize your storage.
4. **Download Files**: Download files from your storage.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
