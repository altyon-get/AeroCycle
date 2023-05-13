# Aircraft Recycling Platform

The Aircraft Recycling Platform is a web application designed to connect aircraft manufacturers, airlines, and recycling facilities to facilitate the repurposing and recycling of end-of-life aircraft components. The platform aims to promote sustainability and reduce waste in the aviation industry.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The aviation industry is under increasing pressure to reduce its environmental impact, and one area where significant progress can be made is in the recycling and repurposing of end-of-life aircraft components. This web application serves as a marketplace and dashboard to connect stakeholders and facilitate the recycling process.

The platform allows aircraft manufacturers and airlines to buy/identify components that are nearing the end of their useful life and arrange for their repurposing or recycling. Recycling facilities can also use the platform to identify sources of recycled materials, including both metals and non-metallic materials such as composites and plastics.

The dashboard provides a clear and concise overview of the key metrics and data related to the recycling and repurposing of end-of-life aircraft components. This includes information on the percentage of materials being recycled or repurposed, environmental impact metrics, and performance metrics.

## Features

- Database of aircraft parts with information on material composition, age, and condition.
- Marketplace functionality for manufacturers and airlines to buy/identify components for repurposing or recycling.
- Material identification and sourcing for recycling facilities.
- Dashboard with visualizations and metrics related to recycling and repurposing efforts.

## Tech Stack

- Backend: Flask (Python)
- Frontend: React (JavaScript)
- Database: MongoDB

## Installation

1. Clone the repository: 
```shell 
git clone <repository-url>
```
2. Install the dependencies for the backend:
```shell 
cd backend
pip install -r requirements.txt
```
3. Install the dependencies for the frontend:
```shell 
cd frontend
npm install
```
4. Set up the MongoDB database and configure the backend to connect to it.


## Usage

1. Start the backend server: 
```shell 
cd backend
python app.py
```
2. Start the frontend development server:
```shell 
cd frontend
npm start
```
3. Access the application in your web browser at http://localhost:3000.

