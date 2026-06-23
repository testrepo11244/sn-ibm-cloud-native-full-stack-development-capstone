# xrwvm-fullstack_developer_capstone

## Project: fullstack_developer_capstone

This repository contains the final capstone project for the IBM Skills Network **Full Stack Application Development** course.  
The application is a **Django** backend paired with a **React** frontend that lets users browse car dealers, view dealer reviews, and submit their own reviews.

### Features
- **User Authentication** – Register, login, logout  
- **Dealer Listings** – View all dealers, filter by state, view dealer details  
- **Review Management** – Submit reviews, view sentiment analysis results  
- **Admin Dashboard** – Manage dealers and reviews (root user)  
- **CI/CD Pipeline** – Automated testing and deployment with GitHub Actions  
- **Live Deployment** – Application deployed on Render/Heroku  

### Technologies Used
- **Backend:** Django, Django REST Framework, PostgreSQL  
- **Frontend:** React.js, Bootstrap 5, Axios  
- **Containerization:** Docker  
- **CI/CD:** GitHub Actions  
- **Deployment:** Render (or Heroku)  

### How to Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/xrwvm-fullstack_developer_capstone.git
cd xrwvm-fullstack_developer_capstone

# Backend
cd server
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend
cd ../frontend
npm install
npm start
```

---  
Feel free to explore the code, raise issues, or contribute!