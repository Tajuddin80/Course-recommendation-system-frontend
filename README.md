# 🎓 Course Recommender – Frontend

Frontend of the **Course Recommendation System**, built with **React, Vite, TailwindCSS, and React Router DOM**.  
This application allows users to explore all courses, view details, and get personalized course recommendations.

---

## 🚀 Features
- 📚 Browse all available courses  
- 🔥 See most popular courses (popularity-based recommendations)  
- 🎯 Get personalized recommendations by User ID (collaborative filtering)  
- 💡 Explore related courses on the Course Details page (content-based)  
- 🌐 Responsive design with TailwindCSS  

---

## 🖥️ Tech Stack
- React 19  
- Vite  
- React Router DOM  
- TailwindCSS  
- Lucide Icons  

---

## 📂 Project Structure

Generated on: 8/17/2025, 8:16:54 PM
Root path: `/media/tajuddin/Work & Study/Study/ML LAB/ML project`

```
├── .git/ 🚫 (auto-hidden)
├── backend/
│   ├── .git/ 🚫 (auto-hidden)
│   ├── __pycache__/ 🚫 (auto-hidden)
│   ├── data/
│   │   ├── courses.csv
│   │   └── ratings.csv
│   ├── models/
│   │   ├── cf_indices.joblib
│   │   ├── cf_svd.joblib
│   │   └── content_model_embeddings.joblib
│   ├── venv/ 🚫 (auto-hidden)
│   ├── app.py
│   ├── collaborative_model.py
│   ├── content_model.py
│   ├── load-data.py
│   ├── popularity.py
│   └── requirements.txt
└── frontend/
    ├── .git/ 🚫 (auto-hidden)
    ├── node_modules/ 🚫 (auto-hidden)
    ├── public/
    │   └── vite.svg
    ├── src/
    │   ├── assets/
    │   │   ├── bannerE.jpg
    │   │   └── react.svg
    │   ├── components/
    │   │   ├── Coursecard.jsx
    │   │   └── Header.jsx
    │   ├── pages/
    │   │   ├──  Recommendations.jsx
    │   │   ├── AllCourse.jsx
    │   │   ├── CourseDetails.jsx
    │   │   └── Home.jsx
    │   ├── App.jsx
    │   ├── index.css
    │   └── main.jsx
    ├── .gitignore
    ├── README.md
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── tailwind.config.js
    └── vite.config.js
```


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/Tajuddin80/Course-recommendation-system-frontend.git
cd course-recommender-frontend


2️⃣ Install dependencies
npm install

3️⃣ Run development server
npm run dev

By default, the frontend runs at:
👉 http://localhost:5173


🔗 API Endpoints (Backend Integration)

The frontend expects these backend endpoints (Flask/Django/FastAPI etc.):

GET /api/courses → All courses
GET /recommend/popularity?top_n=10 → Popular courses
GET /recommend/collaborative?user_id=1&top_n=5 → User-based recommendations
GET /recommend/content?course_id=2&top_n=5 → Related courses



📝 Future Enhancements

Search & filter courses
User authentication (login/signup)
Save favorite courses
Dark mode toggle

👨‍💻 Author

Md Tajuddin
🚀 Full-Stack Developer | Building smart learning tools