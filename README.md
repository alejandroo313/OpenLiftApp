# OpenLiftApp
**OpenLiftApp** is a Open Source is an open source application to keep track of the weights you lift in the gym and your diet

The project uses **Django + Django REST Framework** for the backend and **Angular** for the frontend.

---

## 🚀 Principal technologies

- **Backend:** Django 5.x, Django REST Framework
- **Frontend:** Angular 18+
- **Database:** PostgreSQL
- **Authentication:** JWT (simplejwt)
- **Containers:** Docker

---

## ⚙️ Project structure

```
openliftapp/
├── backend/
├── frontend/
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🧩 Rapid installation (dev mode)

### 🔹 Backend
```bash
cd backend
python -m venv env
source env/bin/activate  # o env\Scripts\activate en Windows
pip install -r requirements.txt
python manage.py runserver
```

### 🔹 Frontend

```bash
cd frontend
npm install
ng serve
```

Then open http://localhost:4200