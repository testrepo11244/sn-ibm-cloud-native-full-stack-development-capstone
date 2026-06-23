# Car Dealership Full‑Stack Application

**Repository:** `github.com/yourusername/car-dealership-fullstack`

**Project Name:** Cloud‑Enabled Car Dealership Application  

This project is a full‑stack web application that combines a Django back‑end with a React front‑end. It allows users to browse car dealers, view dealer details, read and submit reviews, and manage their accounts. The application is containerised, CI/CD‑enabled with GitHub Actions, and deployed to a cloud platform.

---

## Features
- **Dealer Listings** – Browse all dealers or filter by state.  
- **Dealer Detail Page** – View dealer information and customer reviews.  
- **Review Submission** – Authenticated users can post reviews; sentiment analysis is performed on the review text.  
- **User Authentication** – Register, login, and logout using JWT tokens.  
- **Responsive UI** – Built with React, Bootstrap, and custom CSS.  
- **CI/CD Pipeline** – Automated testing and deployment via GitHub Actions.  

---

## Tech Stack
- **Back‑end:** Django 3.2, Django REST Framework, PostgreSQL  
- **Front‑end:** React 18, React Router, Axios, Bootstrap 5  
- **DevOps:** Docker, GitHub Actions, Render (deployment)  

---

## Getting Started
```bash
# Clone the repo
git clone https://github.com/yourusername/car-dealership-fullstack.git
cd car-dealership-fullstack

# Start the development environment
docker-compose up --build
```

For detailed setup instructions, see the `docs/SETUP.md` file.

---

## License
This project is licensed under the MIT License – see the `LICENSE` file for details.