StreamHive
StreamHive is a cutting-edge live streaming platform designed for both streamers and viewers. It integrates essential features for a seamless experience, including RTMP/WHIP streaming, OBS integration, real-time chat, and user interaction tools. This project is built with Next.js (TypeScript) and PostgreSQL for efficient data handling and scalability.

Features
Live Streaming: RTMP and WHIP support for high-quality streams.
Real-Time Chat: Engage with viewers through interactive chat.
User Authentication: Secure user login and registration with JWT tokens.
Streamer Dashboard: Monitor and manage streams, view analytics.
Push Notifications: Get notifications about stream events and user activities.
Database: PostgreSQL for robust and scalable data management.
OBS Integration: Easily set up and start streaming with OBS Studio.

Installation
Prerequisites
Node.js (v16+)
PostgreSQL database
Setup Steps
Clone the repository:
git clone https://github.com/chou27/StreamHive.git
Navigate to the project directory:
cd StreamHive
Install dependencies:
npm install
Create a .env.local file with your environment variables. Example:
DATABASE_URL=postgresql://user:password@localhost:5432/streamhive
JWT_SECRET=your_jwt_secret
Run migrations to set up your database:
npx prisma migrate deploy
Start the development server:
npm run dev
Visit http://localhost:3000 to access the app.

Technologies Used
Next.js (TypeScript) for the frontend and SSR.
PostgreSQL for database management.
Prisma ORM for easy database interaction.
OBS Studio integration for stream setup.
Tailwind CSS for responsive UI design.

Database Structure
User: Handles authentication and profile management.
Stream: Manages live stream information, status, and viewer count.
Chat: Stores messages and user interactions during streams.
Running Tests
To run tests, use:

npm run test
