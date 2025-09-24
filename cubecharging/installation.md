---
title: Installation
parent: CubeCharging
nav_order: 2
---

# Installation

## Prerequisites

Before installing CubeCharging, ensure you have the following:

- Node.js (version 16 or higher)
- npm or yarn package manager
- Git
- Basic understanding of command line tools

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/veds-group/cubecharging.git
cd cubecharging
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Configuration

Copy the environment template and configure your settings:

```bash
cp .env.example .env
```

Edit the `.env` file with your specific configuration:

```env
# Database Configuration
DB_HOST=localhost
DB_PORT=5432
DB_NAME=cubecharging
DB_USER=your_username
DB_PASSWORD=your_password

# API Configuration
API_PORT=3000
API_KEY=your_api_key

# Charging Station Configuration
STATION_ID=your_station_id
MAX_POWER=10000
```

### 4. Database Setup

Initialize the database:

```bash
npm run db:migrate
npm run db:seed
```

### 5. Start the Application

```bash
npm start
```

## Docker Installation

Alternatively, you can use Docker for easier setup:

```bash
docker-compose up -d
```

This will start all required services including the database and application.

## Verification

To verify the installation is working correctly:

1. Open your browser and navigate to `http://localhost:3000`
2. Check the API health endpoint: `http://localhost:3000/api/health`
3. Review the logs for any errors

## Troubleshooting

Common installation issues and solutions:

- **Port already in use**: Change the port in your `.env` file
- **Database connection failed**: Verify your database credentials and ensure the database is running
- **Permission errors**: Ensure you have the necessary permissions for the installation directory
