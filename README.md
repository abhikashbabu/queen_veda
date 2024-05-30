# Next.js + QueenVedas Starter Project
Live Demo: https://nextjs-starter-buttercms.vercel.app/



This Next.js starter project fully integrates with dynamic sample content from your ButterCMS account, including main menu, pages, blog posts, categories, and tags, all with a beautiful, custom theme with already-implemented search functionality. All of the included sample content is automatically created in your account dashboard when you sign up for a free trial of ButterCMS.

A copy of this starter project can be easily and quickly deployed to Vercel or Heroku with the click of a button.
## 1) Installation

First, install the dependencies by cloning the repo and running one of the following commands, depending on your current setup:
```bash
git clone https://github.com/ButterCMS/nextjs-starter-buttercms.git
cd nextjs-starter-buttercms
npm install # or yarn install
```

## 2) Set API Token

To fetch your ButterCMS content, add your API token as an environment variable.

```bash
$ echo 'NEXT_PUBLIC_BUTTER_CMS_API_KEY=<Your API Token>' >> .env
```

## 3) Run the local server

To view the app in a browser, you'll need to run the local development server:

```bash
npm run dev # or yarn dev
```

Congratulations! Your starter project is now live: [http://localhost:3000](http://localhost:3000).

## 4) Deploy

Deploy your Butterized proof of concept app and spread your love of Butter, to either 
Vercel, the creators of Next.js, or to Heroku. With the click of a button, you'll create a copy of our starter project in your Git provider account, instantly deploy it, and institute a full content workflow connected to your ButterCMS account. Smooth.



## 5) Previewing

Your starter project is automatically configured to show draft changes saved in your Butter account when run locally or deployed to a hosting provider. To disable this behavior, set the following value in your .env file: PREVIEW=false.
