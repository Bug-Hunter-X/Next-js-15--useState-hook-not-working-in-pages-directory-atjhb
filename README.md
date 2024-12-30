# Next.js 15 useState Hook Issue in Pages Directory

This repository demonstrates a common issue encountered in Next.js 15 applications when attempting to use the `useState` hook directly within page components located in the `pages` directory.  The `useState` hook, while functional in components within the `app` directory, is not directly accessible in the traditional `pages` directory of Next.js 15 apps.  This example shows the problem and provides a solution.

## Problem

The `bug.js` file showcases a simple Next.js 15 application.  Attempting to use `useState` within the `/pages/about.js` file results in a runtime error because the hook isn't available in that context. 

## Solution

The `bugSolution.js` file demonstrates a corrected approach, utilizing a custom hook to manage state effectively within the `pages` directory.  This approach provides a cleaner and more maintainable way to manage state in Next.js 15 projects, even when working with the `pages` directory.  It adheres to the recommended practices for state management in Next.js applications.  The solution utilizes the `app` directory structure for improved performance and features of Next.js 15.