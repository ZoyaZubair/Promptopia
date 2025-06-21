
# 🎨 Promptopia – AI-Powered Text-to-Image Generator

**Promptopia** is a full-stack AI image generation web app that transforms your text prompts into stunning visuals using modern AI models like **OpenAI’s DALL·E**, **Replicate**, or **Hugging Face**. Built with the **MERN stack**, it provides a minimal yet powerful user experience for generating, viewing, and sharing AI-generated art.

---

## ✨ Features

- 🔮 "Surprise Me" button for random creative prompts  
- 🔍 Search across community-generated art  
- 📸 View hover cards with prompt + username  
- 📤 Share generated images to the public gallery  
- 💾 Download images instantly  
- 💡 Clean, modern design with responsive layouts

---

##  Tech Stack

| Layer       | Technologies                  |
|-------------|-------------------------------|
| Frontend    | React, Tailwind CSS, Vite     |
| Backend     | Node.js, Express              |
| Database    | MongoDB with Mongoose         |
| Cloud       | Cloudinary                    |
| AI APIs     | OpenAI (DALL·E) |

---


## 🛠️ Installation Guide

Here’s how to run **Promptopia** on your local machine:

---

### ✅ 1. Clone the Project

```bash
git clone https://github.com/your-username/Promptopia.git
cd Promptopia
````

---

### 🖥️ 2. Set up the Client

```bash
cd client
npm install
npm run dev
```

* This will start the frontend on `http://localhost:5173`

---

### 🌐 3. Set up the Server

```bash
cd ../server
npm install
```

Create a `.env` file in `/server`:

```env
OPENAI_API_KEY=your_openai_key
MONGODB_URL=your_mongodb_url
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Then run the backend:

```bash
node index.js
```

* Backend runs at `http://localhost:8080`

---

## 🔄 How It Works

1. User types a prompt and clicks **Generate**.
2. Backend sends the prompt to an AI API (OpenAI / Replicate / HF).
3. Generated image is returned (as base64 or URL).
4. User sees the image and can download or share it.
5. If shared, it's saved to MongoDB and uploaded to Cloudinary.
6. The Community section fetches and displays all shared posts.

---

## 📚 What I Learned

Building Promptopia helped me:

* Learn full-stack app development (MERN)
* Integrate external APIs like OpenAI and Replicate
* Manage image uploads with Cloudinary
* Use RESTful routes and async error handling
* Improve frontend layout with TailwindCSS
* Create a smooth user experience from prompt to publish

---

## 🙋‍♀️ About Me

Hi! I’m **Zoya Zubair**, a passionate full-stack developer and tech enthusiast. I love blending AI with beautiful user interfaces and enjoy bringing creative ideas to life through code.

* 🔗 [LinkedIn](https://www.linkedin.com/in/zoya-zubair-62841024b/)
* 💻 [GitHub](https://github.com/ZoyaZubair)

---

> Feel free to fork, explore, and use Promptopia as inspiration for your own AI creations!


