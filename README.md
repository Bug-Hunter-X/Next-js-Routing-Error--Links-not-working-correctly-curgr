# Next.js Routing Bug

This repository demonstrates a common Next.js routing bug and its solution. The bug involves links not working as expected, often leading to 404 errors.

## Bug Description

The provided Next.js application features two pages: a home page and an about page.  The link from the home page to the about page fails, producing an incorrect routing outcome. This may manifest as a 404 error or unexpected page rendering. The root cause is a problem with the path specification or Next.js router configuration. 

## Bug Reproduction

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the homepage (`http://localhost:3000`).
5. Attempt to click the link to the About page.  Observe the routing error.

## Solution

The solution addresses the routing issue by making sure the links are correctly configured according to the Next.js routing conventions.
