

### 🧠 **README.md**

```markdown
# 🚀 DevTrackAI — AI-Driven Developer Productivity Tracker

DevTrackAI is an **AI-powered developer productivity tracking system** built with Django.  
It helps teams, admins, and individual developers monitor performance, analyze commit activity, track projects, and gain insights through intelligent analytics — all within a beautiful, responsive UI.

---

## 🌟 Features

### 👨‍💻 For Developers
- 📅 View personalized **daily & weekly schedules**
- 🔗 **Connect GitHub or other tools** for commit tracking
- 📊 Monitor **previous projects and commits**
- ✅ View and manage **daily tasks**
- 🤖 Get AI-powered **productivity stats and insights**

### 🧑‍💼 For Admins
- 👥 View all registered **developers**
- 🗂️ Track **project status** (upcoming, ongoing, completed)
- 📈 Analyze **developer productivity trends**
- 🔍 Gain **project-level analytics**

---

## 🖼️ Screenshots

| Home Page | Developer Dashboard | Admin Dashboard |
|------------|--------------------|----------------|
| ![Home](static/images/home_preview.png) | ![Dev](static/images/dev_dashboard.png) | ![Admin](static/images/admin_dashboard.png) |

---

## ⚙️ Tech Stack

**Frontend:**  
- HTML, CSS, Bootstrap 5  
- JavaScript (minimal interactivity)

**Backend:**  
- Django 5.0 (no DRF used — pure Django views & templates)  
- SQLite3 (default) / PostgreSQL (for production)

**AI & Analytics (Planned):**  
- Python (Pandas, Scikit-learn, NumPy for metrics)  
- Future: ML model for burnout prediction & code pattern analysis  

**Version Control & Deployment:**  
- GitHub Integration  
- Render / Vercel / Railway for deployment  

---

## 📁 Project Structure

```

DevTrackAI/
│
├── main/                     # Root app: authentication, landing page
│   ├── templates/
│   │   ├── home.html         # Landing page UI
│   │   ├── login.html
│   │   ├── signup.html
│   └── static/
│       ├── css/home.css
│       └── images/
│
├── developer/                # Developer-specific features
│   ├── views.py
│   ├── models.py
│   └── templates/developer/
│
├── adminpanel/               # Admin-specific features
│   ├── views.py
│   ├── models.py
│   └── templates/adminpanel/
│
├── DevTrackAI/               # Project configuration
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
└── manage.py

````

---

## 🧩 Installation & Setup

Follow these steps to run DevTrackAI locally 👇

```bash
# 1️⃣ Clone the repository
git clone https://github.com/<your-username>/DevTrackAI.git
cd DevTrackAI

# 2️⃣ Create and activate virtual environment
python -m venv venv
venv\Scripts\activate   # For Windows
source venv/bin/activate  # For macOS/Linux

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run migrations
python manage.py makemigrations
python manage.py migrate

# 5️⃣ Start the development server
python manage.py runserver
````

Now visit 👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 🔐 Authentication

* Admin & Developer have separate login portals.
* `superuser` can manage all accounts via Django Admin.

To create an admin account:

```bash
python manage.py createsuperuser
```

---

## 💡 Future Enhancements

* 🤖 ML-powered productivity score generation
* 🌍 OAuth integration (GitHub, Slack, Jira)
* 📊 Interactive dashboards using Chart.js
* 💬 Team chat & project updates in real-time
* 🧠 AI model for burnout detection and code review insights

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repo
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📫 Contact

**👤 Author:** Hitesh Tyagi
📧 Email: [support@devtrackai.com](mailto:support@devtrackai.com)
🌐 LinkedIn: [linkedin.com/in/hitesh-tyagi](https://linkedin.com/in/hitesh-tyagi)
💻 GitHub: [github.com/<your-username>](https://github.com/<your-username>)

---

### 💬 “Empower Developers. Predict Burnout. Deliver Smarter.”

Made with ❤️ using **Django + Bootstrap + AI**

```

---


