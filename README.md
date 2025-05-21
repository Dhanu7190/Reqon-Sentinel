# ReQon - AI-Powered Quality Assurance Platform

ReQon is an AI-powered quality assurance platform designed to revolutionize software testing by creating an autonomous, self-learning ecosystem that aligns with Agile methodologies.

## Project Overview

This React application is the frontend interface for the ReQon platform. It provides a comprehensive UI for:

- Testing and monitoring web applications
- Creating and managing feature sets
- Viewing and analyzing test reports
- Configuring settings for the platform

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/reqon-app.git
cd reqon-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.

## Features

- **SSO Authentication**: Login with Google, Microsoft, or GitHub
- **Dashboard**: Overview of testing status with key metrics
- **Feature Sets**: Create and manage test scenarios
- **Reports**: View detailed test execution results
- **Settings**: Configure preferences and integrations

## Project Structure

```
reqon-app/
├── public/              # Static files
├── src/
│   ├── components/      # React components
│   │   ├── auth/        # Authentication components
│   │   ├── common/      # Common UI components
│   │   ├── dashboard/   # Dashboard components
│   │   ├── features/    # Feature set components
│   │   ├── reports/