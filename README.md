# StreamHive

StreamHive is a cutting-edge live streaming platform designed for streamers and viewers. It features high-quality streaming with RTMP/WHIP support, real-time chat, OBS integration, and user interaction tools. Built with **Next.js** (TypeScript) and **PostgreSQL**, StreamHive ensures an efficient and scalable experience.

## Features
- **Live Streaming**: Supports RTMP/WHIP for high-quality streams.
- **Real-Time Chat**: Engage with viewers via live chat.
- **User Authentication**: Secure login and registration.
- **Streamer Dashboard**: Manage streams and view analytics.
- **Push Notifications**: Notifications for stream events.
- **OBS Integration**: Seamless setup with OBS Studio.
- **Database**: Utilizes **PostgreSQL** for data management.

## Installation

### Prerequisites
- Node.js (v16+)
- PostgreSQL database

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/chou27/StreamHive.git
2.Install dependencies:
  ```bash
   npm install
3.Create a .env.local file with the following environment variables:
  ```bash
  DATABASE_URL=postgresql://user:password@localhost:5432/streamhive
JWT_SECRET=your_jwt_secret
4. Run database migrations:
  ```bash
   npx prisma migrate deploy
5. Start the development server:
   ```bash
   npm run dev
6.Visit http://localhost:3000 to see the app in action.
 ```

## Technologies Used
- **Next.js** (TypeScript) for frontend development and server-side rendering (SSR).
- **PostgreSQL** for reliable and scalable database management.
- **Prisma ORM** for efficient database interaction and migrations.
- **OBS Studio** for seamless streaming integration.
- **Tailwind CSS** for building responsive and customizable UI components.
