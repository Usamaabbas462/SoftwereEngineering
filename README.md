# 📦 MediaHub: Open-Licensed Media Search Platform

**OpenMedia Explorer** is a web-based application designed to enable users to search, filter, and preview openly licensed media content using the Openverse API. The platform provides a user-friendly interface with secure authentication, recent search history, and media previews.

---

## 🛠️ Technologies Used

- **Backend:** Django, Django REST Framework
- **Frontend:** HTML, CSS, JavaScript
- **API Integration:** Openverse API
- **Containerization:** Docker & Docker Compose
- **Testing:** Django’s built-in testing framework

---

## 📌 Key Features

- User registration and login (Token-based Authentication)
- Search for images and audio via Openverse API
- Save recent searches for each user
- Lightweight, responsive frontend
- Containerized deployment with Docker
- Scalable modular architecture
- Unit testing for backend logic

---

## 🗂️ Project Structure

```bash
MediaHub/
├── backend/
│   ├── core/            # Django app: APIs, auth, search
│   ├── mediahub/        # Project settings
│   ├── manage.py
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── main.js
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── README.md
