# developer-interview-node

This repository contains a simple Node.js application that serves as a coding challenge for developer interviews. The application is built using Express.js and can be extended to add necessary routes and functionality as needed.

## Getting Started

To get started with this application, follow the instructions below:

### Prerequisites

- Node.js (version 20 or higher)
- npm (version 9 or higher)

You must have Docker and devcontainers installed to run this application in a containerized environment.

### Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:companieshouse/developer-interview-node.git
   ```

2. Navigate to the project directory:

   ```bash
   cd developer-interview-node
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

### Running the Application

To run the application, use the following command:

```bash
npm run start:dev
```

which will start the server in development mode. The application will be accessible at `http://localhost:3000`.

## At the end of the test

### On Unix-based terminals

If you're running within a Unix-based terminal, you can run the following command to create a zip file of your work:

```bash
./bin/zip-my-code
```

This will create a zip file in the root of the project with your code, which you can then share with us.

### Windows PowerShell

If you're operating on Windows, you can create a zip file of your work using the following command in PowerShell:

```powershell
Compress-Archive -Path .\* -DestinationPath techtest-<your-name>.zip
```

Where `<your-name>` should be replaced with your actual name. This command will create a zip file in the root of the project with your code, which you can then share with us.

### Windows File Explorer

If you're using Windows File Explorer, you can create a zip file of your work by following these steps:

1. Navigate to the root directory of the project.
2. Select all the files and folders in the project (you can use Ctrl + A).
3. Right-click on the selected files and choose "Send to" > "Compressed (zipped) folder".
4. Name the zip file as `techtest-<your-name>.zip`, replacing `<your-name>` with your actual name.
5. The zip file will be created in the root of the project, which you can then share with us.
