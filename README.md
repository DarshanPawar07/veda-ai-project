# VedaAI 🚀

An AI-powered assignment and question paper generation platform that helps educators and students create structured academic papers instantly using Generative AI.

## 🌐 Live Demo

**Frontend:** https://veda-ai-frontend-gamma.vercel.app/

**Backend API:** https://veda-ai-backend-production.up.railway.app/

---

## ✨ Features

* Generate complete assignment papers using AI
* Custom assignment title and instructions
* Configure total questions and marks
* Automatic question paper generation
* View generated papers instantly
* Assignment history dashboard
* Detailed paper view with sections and questions
* Responsive user interface
* MongoDB-based data storage
* Railway + Vercel deployment

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* Express.js
* TypeScript
* MongoDB
* Mongoose

### AI Integration

* Groq API
* Google Generative AI

### Queue & Processing

* BullMQ
* Redis

### Deployment

* Vercel (Frontend)
* Railway (Backend)

---

## 📂 Project Architecture

```text
VedaAI
│
├── frontend
│   ├── src/app
│   ├── src/components
│   ├── src/lib
│   └── public
│
├── backend
│   ├── src/controllers
│   ├── src/routes
│   ├── src/models
│   ├── src/services
│   ├── src/utils
│   ├── src/config
│   └── uploads
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/DarshanPawar07/veda-ai-backend.git
```

---

## Backend Setup

```bash
cd backend

npm install
```

Create a `.env` file:

```env
PORT=5000

MONGODB_URI=your_mongodb_uri

REDIS_URL=your_redis_url

GROQ_API_KEY=your_groq_api_key

GOOGLE_API_KEY=your_google_api_key
```

Run backend:

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd frontend

npm install
```

Create `.env.local`:

```env
NEXT_PUBLIC_API_URL=http://localhost:5000
```

Run frontend:

```bash
npm run dev
```

---

## 🚀 Deployment

### Backend (Railway)

```text
Platform: Railway
URL:
https://veda-ai-backend-production.up.railway.app/
```

Environment Variables:

```env
PORT
MONGODB_URI
REDIS_URL
GROQ_API_KEY
GOOGLE_API_KEY
```

---

### Frontend (Vercel)

```text
Platform: Vercel
URL:
https://veda-ai-frontend-gamma.vercel.app/
```

Environment Variable:

```env
NEXT_PUBLIC_API_URL=https://veda-ai-backend-production.up.railway.app
```

---

## 📸 Application Workflow

1. Open the dashboard.
2. Enter assignment title.
3. Add instructions.
4. Select total questions.
5. Select total marks.
6. Click **Generate Paper**.
7. AI generates a complete assignment.
8. View generated paper.
9. Access previous papers through **Recent Papers**.

---

## 🎯 Future Improvements

* User authentication
* Teacher and student dashboards
* Cloud storage for PDFs
* Assignment sharing
* Subject-wise templates
* Difficulty-level customization
* Export to PDF and DOCX
* Analytics dashboard

---

## 👨‍💻 Author

### Darshan Pawar

Software Developer | MERN Stack Developer | AI Enthusiast

GitHub:
https://github.com/DarshanPawar07

LinkedIn:
https://www.linkedin.com/

---

## 📄 License

This project is created for educational and portfolio purposes.
