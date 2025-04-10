# Farmhub

Farmhub is a web-based application designed to provide insights into farm health and crop conditions. It leverages modern web technologies and AI-powered tools to assist farmers in monitoring and improving their crop yields.

---

## Features

- **Frontend**:
  - Built with React and TailwindCSS for a responsive and modern UI.
  - Uses Radix UI components for accessibility and design consistency.
  - Implements animations with `tailwindcss-animate`.

- **Backend**:
  - Express.js server for handling API requests.
  - AI-powered crop analysis using Groq SDK.
  - RESTful API for analyzing crop health based on user input.

- **Environment**:
  - `.env` file for managing sensitive API keys like `VITE_OPENWEATHER_API_KEY`.

- **Styling**:
  - TailwindCSS configuration with custom themes and colors for farm-related visuals (e.g., soil, sky, leaf colors).

---

## Tech Stack

- **Frontend**: React, TailwindCSS, Radix UI
- **Backend**: Express.js, Groq SDK
- **Build Tool**: Vite
- **Database**: Not specified (assumed external APIs for data)
- **AI Integration**: Groq SDK for crop health analysis

---

## Installation Guide

### Prerequisites

Ensure you have the following installed on your system:
- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Git**

### Steps to Clone and Install

1. Open your terminal and navigate to the directory where you want to clone the project.
2. Clone the repository:
   ```bash
   git clone https://github.com/samarthbedare/farmhub.git
3. ```bash
   cd Farmhub
4. Install libraries
    ```bash
    npm install i
5. Install server libraries
    ```bash
    cd data
    npm install i
6. Start server.js
    ```bash
    cd data
    node server.js
7. Run Backend
    (Open new Terminal)
    ```bash
    cd Farmhub
    npm run dev
8. Open Link
    ```bash
    (example)
    PS D:\Samarth\B.E DY Patil Pimpri\DevClash\Farmhub> npm run dev

    > vite_react_shadcn_ts@0.0.0 dev
    > vite


    VITE v5.4.10  ready in 2164 ms

    ➜  Local:   http://localhost:8080/
    ➜  Network: http://192.168.138.107:8080/
    ➜  press h + enter to show help
    Browserslist: browsers data (caniuse-lite) is 6 months old. Please run:
    npx update-browserslist-db@latest
    Why you should do it regularly: https://github.com/browserslist/update-db#readme

