# 📝 n0tepad

**n0tepad** is a simple and personal notes app that helps you store, manage, and remember your thoughts and tasks with ease.

No complicated MongoDB setup required — it's all handled for you using **Docker**! No need to even create or run any networks as docker compose via the yaml file takes care of it.

---

## 🚀 Quick Start

> Follow these steps to get `n0tepad` up and running on your machine in minutes:

### 🛠️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/soham-0-0-7/n0tepad

# 2. Navigate into the project folder
cd n0tepad

# 3. Start MongoDB using Docker Compose
docker compose -f mongodb.yaml up -d

# 4. Start the app
npm run dev
```

#### ENV FILE -
- Create an env file with the variable 
>MONGODB_URI = mongodb://admin:qwerty@localhost:27017/

- admin and qwerty are the username and password set via the yaml file

### Access the Database

- Open your browser and go to: 👉 http://localhost:8081

- Use the following credentials to log in to the MongoDB UI:

>Username: admin<br>
>Password: pass<br>

#### Working ( video ) - https://drive.google.com/file/d/146JpMqQuDwHQxAu1-2XNXNswcKeGEiZF/view?usp=drive_link



