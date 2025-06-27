
# TutorMate Frontend (React)

This is the frontend React app for TutorMate AI, designed to connect with a Flask backend running IBM Granite.

## 🚀 Deployment Steps

### 1. Upload to GitHub
- Create a new repository (e.g. `tutormate-frontend`)
- Upload all files from this folder to that repository

### 2. Deploy on Netlify
- Go to https://netlify.com
- Click "New site from Git"
- Choose GitHub, and select your `tutormate-frontend` repo
- Use these settings:
  - **Build command**: `npm run build`
  - **Publish directory**: `build`

### 3. Important
Make sure your backend is deployed to Render and available at:

```
https://your-backend-url.onrender.com
```

Update the backend URL in `src/GraniteChat.jsx` if needed.

---
Built with ❤️ using React and IBM Granite.
