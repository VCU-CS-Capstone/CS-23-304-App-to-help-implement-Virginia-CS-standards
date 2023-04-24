This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
Enviroment:
  - The build enviroment we used, and the perfered one for this app, is Windows OS or Mac OS. We also used Visual Studio Code (or VS Code) for our IDE.

What to download to run:
  Node.js
  - Before execution, run the command "npm install" in the project folder to install all necessary dependencies
  MySQL
  - MySQL is the SQL database we used, and the extention "SQLtools" on VS Code should be dowloaded as well to be able to interact with the database
  - Please refer to the "db.js" file in the "config" folder for the information to access the databse. (The program should auto-connect to the database though)

To run the development server:
  - Run the command "npm run dev" in the terminal for VS Code

Quick note for the CSV download:
  - The CSV download happens in the overview page, when clicking submit, it will automatially initiate a download for a CSV with all the necessary information.

Quick suggested solution for a serverless database - SQLlite
  - We understand that a static website was desired, but due to time constraints we were not able to implement that. As a suggestion, however, SQLite is a good     alternative to achieve that. SQLite is a more lightweight and independent database than MySQL. It doesn't require a seperate server process like MySQL. It is also a self-contained datasystem that sores data in a single file, making it easy to deploy and manage.


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/Schools](http://localhost:3000/api/Schools). This endpoint can be edited in `pages/api/Schools.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

