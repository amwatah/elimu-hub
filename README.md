# Elimu-hub

Elimu hub is a fullblown online learning platform management system that allows tutors and learners to share knowledge via video and other resources.

Key Features:

- Browse & Filter Courses
- Purchase Courses using Mpesa (work in progress)
- Mark Chapters as Completed or Uncompleted
- Progress Calculation of each Course
- Student Dashboard
- Tutor mode
- Create new Courses
- Create new Chapters
- Easily reorder chapter position with drag n’ drop
- Upload thumbnails, attachments and videos
- Video processing
- HLS Video player
- Rich text editor for chapter description
- Authentication

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

Clone this repo

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

MUX_TOKEN_ID=
MUX_TOKEN_SECRET=

NEXT_PUBLIC_APP_URL=http://localhost:3000

```

### Setup Prisma

Add any SQL Database (I used Neon -severless Postgres )

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```
