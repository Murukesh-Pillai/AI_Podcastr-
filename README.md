<h3 align="center">AI Podcast Platform</h3>

<h4 align="center">Wireframe</h4>

![Screenshot 2024-10-19 at 2 21 18 AM](https://github.com/user-attachments/assets/7d34aa30-d0c9-40f8-b9f8-6a7903852116)


## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets (Code to Copy)](#snippets)
6. 🔗 [Assets](#links)
7. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>

A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail Image generation and seamless playback. 

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Convex
- OpenAI
- Clerk
- ShadCN
- Tailwind CSS

## <a name="features">🔋 Features</a>

**Robust Authentication**: Secure and reliable user login and registration system.

**Modern Home Page**: Showcases trending podcasts with a sticky podcast player for continuous listening.

**Discover Podcasts Page**: Dedicated page for users to explore new and popular podcasts.

**Fully Functional Search**: Allows users to find podcasts easily using various search criteria.

**Create Podcast Page**: Enables podcast creation with text-to-audio conversion, AI image generation, and previews.

**Multi Voice AI Functionality**: Supports multiple AI-generated voices for dynamic podcast creation.

**Profile Page**: View all created podcasts with options to delete them.

**Podcast Details Page**: Displays detailed information about each podcast, including creator details, number of listeners, and transcript.

**Podcast Player**: Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.

**Responsive Design**: Fully functional and visually appealing across all devices and screen sizes.

and many more, including code architecture and reusability 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/jsm_podcastr.git
cd jsm_podcastr
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
```

Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the [Convex](https://www.convex.dev/) and [Clerk](https://clerk.com/) websites.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

