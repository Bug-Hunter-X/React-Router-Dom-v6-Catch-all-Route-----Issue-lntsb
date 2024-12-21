# React Router Dom v6 Catch-all Route (*) Issue

This repository demonstrates a common issue encountered when using the catch-all route (`path="*"`) in React Router Dom v6. The problem is that the catch-all route is unexpectedly triggered, overriding other defined routes.

The `App.js` file contains the buggy code, while `AppSolution.js` provides a corrected version.  The issue is explained in detail in the file comments.

## Solution

The solution involves ensuring that the catch-all route is placed at the end of the route list within the `Routes` component.