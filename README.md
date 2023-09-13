# Bird-Clone: A Twitter Clone

Bird-Clone is a Twitter clone web application built using Prisma, MongoDB, and Tailwind CSS. It replicates the core functionality of Twitter, allowing users to post tweets, like, comment, and follow other users.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Authentication: Secure user registration and login.
- User Profiles: User profiles with profile pictures and bio.
- Tweeting: Post tweets with text and images.
- Liking and Commenting: Interact with tweets by liking and leaving comments.
- Following: Follow and unfollow other users to see their tweets.
- Real-time Updates: Real-time updates of tweets and notifications.
- Responsive Design: Mobile-friendly design powered by Tailwind CSS.
- Database: MongoDB database with Prisma ORM.

## Getting Started

### Prerequisites

Before you can run the Bird-Clone application, make sure you have the following prerequisites installed on your system:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community)
- Git: [Download and Install Git](https://git-scm.com/downloads)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/PriDhingra/bird-clone.git
2. Go into the project directory:

   ```bash
   cd bird-clone
3. Go into the project directory:

   ```bash
   npm install

### Configuration

1. Create a .env file in the root directory of the project and add the following environment variables:

   ```bash
   DATABASE_URL=YOUR_DATABASE_URL
   NEXTAUTH_JWT_SECRET=YOUR_NEXTAUTH_JWT_SECRET
   NEXTAUTH_SECRET=YOUR_NEXTAUTH_SECRET


  Replace YOUR_MONGODB_CONNECTION_STRING with your MongoDB connection string, and YOUR_SESSION_SECRET with a secret key for session management.

2. Configure Prisma by running the following command and following the prompts:

   ```bash
   npx prisma generate

### Usage

1. Start the development server:

   ```bash
   npm run dev

2. Access the application in your web browser at http://localhost:3000.
