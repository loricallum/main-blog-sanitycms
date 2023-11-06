# Blog Template - Next.js & Sanity CMS

JAMStack Blog template built with Next.js, Tailwind CSS & Sanity CMS 

# Manual Installation

We recommend you to use the one-click deploy option above. For some reason, if you cannot, use the following steps to install it manually.

## Step 1. Clone the Repo

Clone the github repo or use the downloaded files in your local machine.

## Step 2. Setup `.env` Variables.

Open the project folder and rename `.env.local.example` placed in the root folder into `.env.local` and add your sanity project ID. You can create a new project by visiting this link: https://www.sanity.io/get-started/create-project

If you already have a project, copy the project ID from https://sanity.io/manage

```
NEXT_PUBLIC_SANITY_PROJECT_ID=xxyyzz
```

## Step 3. Allow CORS Origins

To make the studio work properly, you must add CORS origin in Sanity. This is usually setup automatically if you are using the Vercel Deploy. Visit `https://www.sanity.io/manage/personal/project/<project-id>/api` in your browser to add CORS origin.

Click `Add CORS origin` button and enter the URL as `http://localhost:3000` and check the Allow credentials checkbox.

## Step 4 Continue from above steps

Now, you will be able continue from the above instructions to import the demo data and running the project locally.

## Help and Support

Something's not working as expected? Raise a github issue. I
