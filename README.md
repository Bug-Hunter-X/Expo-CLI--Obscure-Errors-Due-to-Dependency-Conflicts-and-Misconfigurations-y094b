# Expo CLI: Obscure Errors Due to Dependency Conflicts and Misconfigurations

This repository demonstrates a common issue encountered when using the Expo CLI: obscure errors arising from dependency conflicts or misconfigurations within the project's dependencies and configuration files (`package.json`, `app.json`).

The `bug.js` file showcases a project setup that leads to these types of errors.  The `bugSolution.js` file provides the corrected version with explanations of the fixes.

## Setup

1. Clone the repository
2. Navigate to the project directory
3. Run `npm install`
4. Attempt to start the Expo development server using `expo start` (observe the error).
5. Review the solution in `bugSolution.js` and implement the necessary changes.
6. Run `expo start` again to verify that the problem is resolved.

## Contributing

Contributions are welcome! If you encounter other variations of this problem or have additional solutions, please feel free to open a pull request.