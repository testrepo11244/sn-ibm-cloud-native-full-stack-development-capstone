# Cloud‑Native Car Dealership

**Repository:** `ibm-cloud-native-car-dealership`  
**Project Name:** Cloud‑Native Car Dealership (Django + React)

This repository contains the source code for a full‑stack car‑dealership web application built with:

* **Backend:** Django REST Framework exposing dealer, car‑make/model and review APIs.  
* **Frontend:** React (Create‑React‑App) consuming the APIs and providing a modern UI.  
* **CI/CD:** GitHub Actions workflow that builds, tests and deploys the app to IBM Cloud.  

The project demonstrates authentication (login/logout), dealer browsing, review submission with sentiment analysis, and a responsive static site for the About and Contact pages.

---  

## Project Structure (high‑level)

```
/server
│   manage.py
│   requirements.txt
│   Dockerfile
│
├───backend
│   ├───api
│   │   ├───views.py
│   │   ├───serializers.py
│   │   └───urls.py
│   └───templates
│       └───index.html
│
└───frontend
    ├───static
    │   ├───About.html
    │   ├───Contact.html
    │   └───css
    │       └───style.css
    └───src
        └───components
            └───Register
                └───Register.jsx
```

---  

## Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/your‑username/ibm-cloud-native-car-dealership.git
   cd ibm-cloud-native-car-dealership
   ```

2. Follow the **README** inside the `server` folder for detailed setup instructions.

---  

## License

MIT License – see the `LICENSE` file for details.