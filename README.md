# Astrastellar-task
# Gallery App

The Gallery App is a full-stack web application built using the [create-t3-app](https://create.t3.gg/). It allows users to preview, post, and like pictures. Users need to sign in to post pictures and like them.

## Features

- **Previewing Posted Pictures**: All users can preview posted pictures.
- **Posting Pictures**: Only logged-in users can post pictures.
- **Likes System**: Only logged-in users can like posted pictures, including their own.

## Technologies Used

- **Frontend**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/), [TailwindCSS](https://tailwindcss.com/)
- **Backend**: [tRPC](https://trpc.io/), [Next.js App Router](https://nextjs.org/docs/app)
- **Database**: [Neon Database](https://neon.tech/docs/guides/nextjs) with [Prisma](https://www.prisma.io/)
- **Authentication**: [NextAuth](https://next-auth.js.org/)
- **Data Fetching**: [TanStack React Query](https://tanstack.com/query/latest)
- **Image Upload**: [UploadThings](https://docs.uploadthing.com/getting-started/appdir)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- PostgreSQL database (Neon or any other PostgreSQL service)
- Google or Discord account for OAuth authentication

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/gallery-app.git
cd gallery-app
2. Install the dependencies:
npm install

3. Edit .env file in the root directory

4. Set up the Prisma schema:
 npx prisma migrate dev --name init
 npx prisma generate

5 Start the development server:
npm run dev


# gallery-app
