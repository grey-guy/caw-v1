---

# CAW


---

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Cloning the Repository](#cloning-the-repository)
  - [Installing Dependencies](#installing-dependencies)
- [Running the Application](#running-the-application)
- [Additional Tips](#additional-tips)
- [Troubleshooting](#troubleshooting)
- [License](#license)

---

## Prerequisites

Ensure your environment meets the following requirements before proceeding:

### 1. Install Node.js and npm

- **Node.js** (version 18.x or higher) is required to run React and Node applications.
- **npm** (Node Package Manager) comes bundled with Node.js.

**Installation Guides:**

- [Download Node.js](https://nodejs.org/)  
  Follow the instructions for your operating system (Mac, Linux, Windows).

### 2. Install Git

- Git is needed to clone the repository.

**Installation Guides:**

- [Download Git](https://git-scm.com/downloads)  
  Follow the instructions for your operating system.

### 3. (Optional) Install a Code Editor

- Recommended: [Visual Studio Code](https://code.visualstudio.com/)

---

## Getting Started

### 1. Clone the Repository

Open your terminal (Mac/Linux) or Command Prompt/PowerShell (Windows), then run the command that you can see if you click the ***clone*** button on bitbucket UI.


### 2. Navigate into the Project Directory

```bash
cd main
```

### 3. Install Dependencies

Run the following command to install all required dependencies:

```bash
npm install
```

---

## Running the Application

### 1. Start the Development Server

Execute:

```bash
npm run dev
```

*This command usually runs scripts like `webpack-dev-server` or `concurrently` to start both backend and frontend servers.*

### 2. Access the Application

Once the server is running, open your web browser and navigate to:

```
http://localhost:3000/
```

*The port number may vary; check your terminal output for the exact URL.*

---

## Additional Tips

- **Running on different operating systems:**
  - On **Mac/Linux**, you can use Terminal.
  - On **Windows**, use Command Prompt, PowerShell, or Windows Terminal.
  
- **Permission issues:**  
  If you encounter permission errors, try running commands with `sudo` (Linux/Mac) or run the terminal as Administrator (Windows).

- **Keep dependencies updated:**  
  Regularly update Node.js and npm to avoid compatibility issues.

- **Using IDEs:**  
  Use code editors like Visual Studio Code for better development experience, with extensions for JavaScript/React.

---

## Troubleshooting

- **Node.js or npm not recognized:**  
  Ensure they are installed correctly and added to your system PATH.

- **Installation errors:**  
  Delete `node_modules` folder and run `npm install` again:

  ```bash
  rm -rf node_modules
  npm install
  ```

- **Port conflicts:**  
  If port 3000 is occupied, change the port in your server configuration or stop the conflicting service.

- **Dependencies fail to install:**  
  Check your internet connection and npm registry status. Clear cache if needed:

  ```bash
  npm cache clean --force
  ```

---
