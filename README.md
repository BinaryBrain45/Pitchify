<div align="center">
  <br />
  <a href="#">
    <img src="https://github.com/user-attachments/assets/655f40c2-af60-4f19-9bae-76f141fc457d" alt="Project Banner">
  </a>
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Sanity-black?style=for-the-badge&logoColor=white&logo=sanity&color=F03E2F" alt="sanity" />
  </div>
  <h3 align="center">Startup Directory Platform</h3>
</div>

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)

## Introduction

A Next.js 15 platform where entrepreneurs can submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a clean minimalistic design for a smooth user experience.

## Tech Stack

- React 19
- Next.js 15
- Sanity
- TailwindCSS
- ShadCN
- TypeScript

## Features

👉 **Live Content API**: Displays the latest startup ideas dynamically on the homepage using Sanity's Content API.
👉 **GitHub Authentication**: Allows users to log in easily using their GitHub account.
👉 **Pitch Submission**: Users can submit startup ideas, including title, description, category, and multimedia links (image or video).
👉 **View Pitches**: Browse through submitted ideas with filtering options by category.
👉 **Pitch Details Page**: Click on any pitch to view its details, with multimedia and description displayed.
👉 **Profile Page**: Users can view the list of pitches they've submitted.
👉 **Editor Picks**: Admins can highlight top startup ideas using the "Editor Picks" feature managed via Sanity Studio.
👉 **Views Counter**: Tracks the number of views for each pitch instead of an upvote system.
👉 **Search**: Search functionality to load and view pitches efficiently.
👉 **Minimalistic Design**: Fresh and simple UI with only the essential pages for ease of use and a clean aesthetic.
and many more, including the latest **React 19**, **Next.js 15** and **Sanity** features alongside code architecture and reusability.

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/BinaryBrain45/Pitchify.git
cd Pitchify
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_SANITY_PROJECT_ID=
NEXT_PUBLIC_SANITY_DATASET=
NEXT_PUBLIC_SANITY_API_VERSION='vX'
SANITY_TOKEN=
AUTH_SECRET=
AUTH_GITHUB_ID=
AUTH_GITHUB_SECRET=
```

Replace the placeholder values with your actual Sanity credentials. You can obtain these credentials by signing up and creating a new project on the [Sanity website](https://www.sanity.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
