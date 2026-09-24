# 🍔 Maxway Fast Food Delivery Web App (Django)

![Django](https://img.shields.io/badge/Django-4.2+-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Frontend-HTML5_CSS3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A full-featured fast food delivery and online ordering web application inspired by **Maxway**, built using **Django**, **Bootstrap**, and **Docker**.

---

## 🌟 Key Features

- **🍔 Menu Catalog (`food`)**: Browse fast food categories (burgers, lavash, drinks, desserts) with pricing and detailed views.
- **📊 Admin Dashboard (`dashboard`)**: Management interface for updating inventory, order statuses, and food items.
- **🛒 Cart & Order Flow**: Shopping cart management and customer order submission.
- **🐳 Dockerized Deployment**: Includes `Dockerfile` and `docker-compose.yml` for multi-container deployment.
- **🎨 Responsive UI**: Modern frontend templates with custom media asset support.

---

## ⚙️ Quick Start

### Running Locally

```bash
git clone https://github.com/Juravoyev/maxway.git
cd maxway

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt

python manage.py migrate
python manage.py runserver
```
Visit `http://127.0.0.1:8000/`.

---

### Running with Docker 🐳

```bash
docker-compose up --build -d
```

---

## 👨‍💻 Author

**Shams Juravoyev**  
- Telegram: [@Juravoyev](https://t.me/Juravoyev)  
- LinkedIn: [Shams Juravoyev](https://www.linkedin.com/in/shams-juravoyev-3017473ab/)  
- GitHub: [@Juravoyev](https://github.com/Juravoyev)  