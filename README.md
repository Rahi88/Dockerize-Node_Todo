# 📝 Node.js Todo API (Dockerized)

This is a simple Node.js-based Todo API built using Express.js.  
It demonstrates how to Dockerize a basic RESTful API without a database.

## 🛠 Features

- ✅ RESTful API with Express.js  
- ✅ In-memory task storage (no DB)  
- ✅ Dockerized for easy setup and execution

## 🚀 Quick Start (Using Docker)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Rahi88/Dockerize-Node_Todo.git
cd Dockerize-Node_Todo
````

### 2️⃣ Build the Docker Image

```bash
docker build -t todo-api-with-node .
```

### 3️⃣ Run the App

```bash
docker run -p 5000:5000 todo-api-with-node
```

### 4️⃣ Open in Browser or Use API Client

Visit: [http://localhost:5000](http://localhost:5000)

## 💡 Run Without Docker

You can also run this app manually:

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Start the App

```bash
node server.js
```

## 🔧 Technologies Used

* Node.js 18 (slim)
* Express.js
* Docker

## 📁 File Highlights

* `server.js` → Main entry point with routing logic
* `Dockerfile` → Contains image build steps
* `.dockerignore` → Prevents unnecessary files from being added to Docker image

## 📌 Notes

* App listens on port **5000** by default
* Ideal for beginners learning Docker and Node.js APIs without DB integration


