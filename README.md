# JSX Comment Error in Next.js 15

This repository demonstrates a bug in Next.js 15 where including a comment within a JSX component's return statement throws an error.  The issue arises when using a standard JSX comment `{/* ... */}`.  This bug is unexpected, as JSX comments are generally supported without problems in other React environments.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.

You'll observe the error in the console during the development process.  The solution demonstrates a workaround to mitigate this issue.