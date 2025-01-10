# React Router: Handling Unmatched Routes
This example demonstrates a common issue in React Router applications: what happens when a user navigates to a route that hasn't been explicitly defined in your `Routes` component?
Without a catch-all route, the application will likely crash or display an error.  The solution involves adding a route that handles any unmatched path.

## The Bug
The `App.js` file contains a simple React Router setup with routes for '/' and '/about'.  However, if the user navigates to a path like '/nonexistent', the app will not handle this gracefully. 

## The Solution
The `AppSolution.js` file demonstrates how to add a catch-all route using the '*' path wildcard to handle any unmatched routes.  This ensures a more user-friendly experience and prevents unexpected application crashes. 