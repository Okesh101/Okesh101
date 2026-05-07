# Hi there 👋, I'm Goodluck

I am a ***Backend Engineer***.

I build backend systems, APIs, and scalable web applications.

Currently focused on **Flask**, while actively learning **Node.js + Express** for modern backend development.

I also maintain a strong interest in **Robotics** and **System Programming** using **C++**.

---

## 🛠️ Tech Stack

### Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSharp](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

### Backend Frameworks
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![CrowCpp](https://img.shields.io/badge/Crow_Cpp-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white)

### Frontend Collaboration
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 💡 About Me

- 🔭 Building backend systems and APIs
- 🌱 Currently learning Node.js & Express
- 🤖 Interested in Robotics and AI systems
- 🧠 Strong interest in scalable backend architecture
- 🚀 Participated in hackathons and collaborative projects
- ⚡ Backend-focused developer who enjoys building real systems

---

# 👨‍💻 Backend Engineer — In Different Languages

### 🐍 Python + Flask
```python
from flask import Flask, jsonify

app = Flask(__name__)

@app.route("/")
def about_me():
    return jsonify({
        "name": "Goodluck",
        "role": "Backend Engineer",
        "stack": ["Flask", "Python", "APIs", "AI Systems"],
        "goal": "Building scalable backend systems"
    })

if __name__ == "__main__":
    app.run(debug=True)
```

### 🚂 Node.js + Express
```javascript
const express = require('express');
const app = express();
app.use(express.json());

app.get('/', (req, res) => {
    res.json({
        name: 'Goodluck',
        role: 'Backend Engineer',
        stack: ['Express', 'Node.js', 'APIs']
    });
});

app.listen(3000, () => {
    console.log('Backend server running...');
});
```

## ⚡ ASP.NET

```csharp
var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();

app.MapGet("/", () => new {
    name = "Goodluck",
    role = "Backend Engineer",
    stack = new[] { "ASP.NET", "C#", "APIs" }
});

app.Run();
```

## ⚙️ C++ + Crow

```cpp
#include "crow.h"

int main()
{
    crow::SimpleApp app;

    CROW_ROUTE(app, "/")([](){
        return crow::json::wvalue({
            {"name", "Goodluck"},
            {"role", "Backend Engineer"},
            {"stack", "C++ | Crow | APIs"}
        });
    });

    app.port(18080).multithreaded().run();
}
```

---

### 🌍 Connect With Me

- X (Twitter): @goodluckdev
- Instagram: @goodluck_dev
- Dev.to: goodluckdev

---

> "Backend developers quietly power the internet."
