# IPO Web Application & REST API Development

## Project Overview
This project involves developing an IPO Web Application and REST API for **Bluestock Fintech**. The application provides IPO-related information to the public, displaying details such as company name, logo, price band, opening and closing dates, listing details, and downloadable reports.

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Development Guidelines](#development-guidelines)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Submission Guidelines](#submission-guidelines)
- [Resources](#resources)
- [Team](#team)

## Objective
The goal of this project is to develop:
1. A web application providing IPO-related information.
2. A REST API to serve data for both the **Bluestock website/app** and **clients' platforms**.

### The application will display:
- Company Name & Logo
- IPO Price & Listing Price
- Open & Close Dates
- Issue Size & Type
- Listing Date & Status
- Current Market Price (CMP) & Return
- Downloadable RHP & DRHP PDFs

## Tech Stack
### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose ORM)
- **API**: RESTful API with JWT authentication
- **Tools**: Postman (API Testing), Git & GitHub (Version Control)

### Frontend
- **Library**: React.js
- **State Management**: Redux (if required)
- **Styling**: CSS/SCSS, Bootstrap 5
- **IDE**: Visual Studio Code (VS Code)

## Features
- Fetch and display IPO details
- REST API integration for data sharing
- Secure and optimized data handling
- User-friendly UI with React.js & Bootstrap 5
- Downloadable IPO-related PDFs

## Development Guidelines
- Follow high-quality, industry-standard coding practices.
- Test features regularly to ensure functionality.
- Implement security measures to protect data integrity.
- Use **Nomon** for task assignment and tracking.

## Prerequisites
Developers should be familiar with:
- **Stock Market Basics** → [Stock Market Introduction](https://youtu.be/Zt6bVL39b9M)
- **IPO Concepts** → [What is IPO?](https://youtu.be/gWrR5qPEmWE)

## Getting Started
1. Clone the repository:
   ```sh
   git clone <repo-url>
   ```
2. Install dependencies:
   ```sh
   cd backend && npm install
   cd ../frontend && npm install
   ```
3. Set up environment variables (`.env` file in the root directory):
   ```env
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
   PORT=5000
   ```
4. Run the backend server:
   ```sh
   cd backend
   npm start
   ```
5. Run the frontend app:
   ```sh
   cd frontend
   npm start
   ```

## Submission Guidelines
- Do **not** commit buggy or error-prone code.
- Test your code locally before pushing.
- Use **main** branch for final submissions.

## Resources
- **UI/UX Design**: [Figma Prototype](https://www.figma.com/design/Y78Wmi24Jdo6PrAFiHySkg)
- **System Design**: [Figma System Design](https://www.figma.com/board/g9bjreevYNJkfMuwRacyaP)
- **Project Assets** (Logos, SVGs, PNGs): [Google Drive Link](https://drive.google.com/drive/folders/1yH9Y_mIqqEkZXtzhqHSuFtEwFOr8BXH5?usp=drive_link)

## Team
| Name                 | Role         | Email                           |
|----------------------|-------------|---------------------------------|
| **Adarsh Kumar Maurya** | Team Lead   | 22.adarsh.03@gmail.com          |
| Gulshan Chauhan     | Co-Team Lead | okaygulshan@gmail.com          |
| Dev Shubhankar      | Developer    | shubhankarrai007@gmail.com     |
| Himanshu Bandiwadekar | Developer    | bandiwadekarhimanshu@gmail.com |
| Om Makwana         | Developer    | ommakwana1406@gmail.com        |
| Durga Prasadu Bomminayuni | Developer    | prasadbommi12345@gmail.com     |
| Sunny Ramnagina Yadav | Developer    | sunnyyadav.developer@gmail.com |
| Yugant Chaudhury   | Developer    | yugant.work@gmail.com          |

## Contact
For any queries, reach out to:  
📧 **hello@bluestock.in**  
🌐 **[Bluestock Fintech Website](http://www.bluestock.in)**

