# Next.js 15 Routing Issue: Blank Page on Navigation

This repository demonstrates a strange routing issue in Next.js 15 where a page renders blank after navigation.

## Bug Description

The application consists of a Home page (`pages/index.js`) and an About page (`pages/about.js`).  Navigating from the Home page to the About page using a Next.js Link results in the About page appearing completely blank, despite no errors appearing in the console.  The About component renders correctly when tested outside the Next.js framework.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Navigate to the `/about` route. The About page will appear blank.

## Expected Behavior

The About page should display "About Page" as defined in `pages/about.js`.

## Actual Behavior

The About page appears blank.

## Solution

The issue can be solved by using a simple fix. Refer to the `solution` branch for the fixed code or view the solution section below.