![Flitwick](https://socialify.git.ci/Artemiskgg1/Flitwick/image?description=1&language=1&name=1&owner=1&pattern=Solid&theme=Dark)

Flitwick is a **Trello-inspired task management application** built using **Next.js, Prisma, PostgreSQL, and Clerk for authentication**. It allows users to create boards, lists, and tasks, helping them organize work efficiently.

## 🚀 Features

- **User Authentication** (Powered by Clerk)
- **Create, Update, and Delete Boards**
- **Drag and Drop Lists & Tasks**
- **Persistent Data Storage** (PostgreSQL with Prisma)
- **Real-time Updates**
- **Dark Mode Support** (using `next-themes`)

## 🛠️ Tech Stack

- **Frontend:** Next.js, Tailwind CSS, Framer Motion (for animations)
- **Backend:** Next.js API Routes, Prisma ORM
- **Database:** PostgreSQL (Hosted on Neon Console)
- **Authentication:** Clerk

## 📦 Installation & Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/Artemiskgg1/Flitwick.git
   cd flitwick
   ```

2. Install dependencies:

   ```sh
   npm install  # or yarn install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add:

   ```env
   DATABASE_URL=your_postgresql_connection_url
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_frontend_api
   CLERK_SECRET_KEY=your_clerk_api_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_OUT_URL=/
   NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=unsplash_api_key
   ```

4. Run database migrations:

   ```sh
   npx prisma migrate dev
   ```

5. Start the development server:
   ```sh
   npm run dev  # or yarn dev
   ```

## 📜 License

This project is licensed under the MIT License.

## ✨ Acknowledgments

- Inspired by Trello & [Code with Antonio](https://youtu.be/pRybm9lXW2c?si=t3NbY05NYIOOTP0F)
- Built with 💙 by [Abha Ghildiyal](https://github.com/artemiskgg1)
