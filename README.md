<!-- ═══════════════════════════════════════════════════════ -->
<!--                   HEADER / BANNER                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=900&size=46&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=850&height=100&lines=%E2%9C%A6+ASHISH+CHERIAN+%E2%9C%A6" alt="Ashish Cherian" />

<br/>

![Full Stack](https://img.shields.io/badge/Full_Stack_Developer-🚀-0d1117?style=for-the-badge&labelColor=0d1117&color=00F7FF)
![Android](https://img.shields.io/badge/Android_Developer-📱-0d1117?style=for-the-badge&labelColor=0d1117&color=FF6EC7)
![AI/ML](https://img.shields.io/badge/AI%2FML_Explorer-🤖-0d1117?style=for-the-badge&labelColor=0d1117&color=a855f7)

<br/><br/>

🎓 **Final-year CSE** @ Karavali Institute of Technology, Mangalore &nbsp;|&nbsp; 📊 **CGPA: 8.0** &nbsp;|&nbsp; 🎯 **Graduating 2026** &nbsp;|&nbsp; 📍 Karnataka, India

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=orange)](https://portfolio-green-nine-18.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashish-cherian-158b49356)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ash_ashish_1_5)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashishcherian15@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=AshishCherian15&label=Profile+Views&color=0891b2&style=flat)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ABOUT ME                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🧠 What I Build

> I build intelligent systems that combine AI with real-world applications.  
> Focused on solving meaningful problems with scalable, production-ready tech.

- 🔭 Currently building **Android Apps, Full Stack Web Apps & AI Tools**
- 🌱 Exploring **Generative AI in Mobile Development**
- 🤝 Open to **Open Source Contributions & Collaboration**
- 💬 Ask me about **Python · Django · Flask · FastAPI · React**
- ⚡ Built an **AI Study Bot with Memory** using **LLaMA 3.3 + Groq**
- 📫 Reach me at: **ashishcherian15@gmail.com**

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   PROJECTS                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🚀 Projects That Matter

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AI Study Bot with Memory
> AI-powered Study Assistant with session memory  
> **FastAPI · Groq (LLaMA 3.3) · MongoDB Atlas**

- ✨ Remembers your full conversation history
- ⚡ Smart, context-aware responses
- 📚 Personalized learning experience

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AshishCherian15/study-bot)

</td>
<td width="50%" valign="top">

```python
# study-bot — Core Logic
@app.post("/chat")
async def chat(msg: str, session: str):
    history = memory.get(session, [])
    history.append({
        "role": "user",
        "content": msg
    })
    res = groq.chat(
        model="llama-3.3-70b",
        messages=history
    )
    memory[session] = history  # persist
    return {"reply": res}
```

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🏭 Multi-Stock Logistics Platform
> Enterprise-grade warehouse & logistics system  
> **Django · PostgreSQL · Real-time Analytics**

- 📦 Inventory tracking & stock management
- 🛒 Multi-vendor marketplace
- 📊 Analytics dashboard with insights

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AshishCherian15/Multi-Stock-Logistics-Platform)

</td>
<td width="50%" valign="top">

### 🎬 Movie Recommender System
> Content-based recommendation engine  
> **Python · TF-IDF · Cosine Similarity**

- 🎯 Smart content-based recommendations
- ⚡ Fast similarity computation
- 🌐 Interactive web UI

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AshishCherian15/Movie-Recommender-System)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💊 Pharmacy Supply Management
> Full-stack pharmacy management system  
> **Flask · SQLite · Role-based Access**

- 🔐 Admin & customer roles
- 📦 Order tracking & audit logs
- 📊 Analytics dashboard

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AshishCherian15/Pharmacy-Supply-Management-System)

</td>
<td width="50%" valign="top">

### 💰 Pay Track — Expense Tracker
> Modern expense tracker web app  
> **TypeScript · AI-assisted frontend**

- 💳 Daily expense tracking
- 📈 Visual spending stats
- ⚡ Clean, fast UI

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AshishCherian15/pay-track)

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   TECH STACK                          -->
<!-- ═══════════════════════════════════════════════════════ -->

## ⚡ Tech Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=python,js,ts,kotlin,java,html,css,c,cpp&perline=9" />
<img src="https://skillicons.dev/icons?i=django,flask,fastapi,react,nextjs,nodejs,express,bootstrap,vite&perline=9" />
<img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,sqlite,supabase,vercel,git,github,postman&perline=9" />

<br/><br/>

**Languages**

![Python](https://img.shields.io/badge/Python-90%25-3776AB?style=flat-square&logo=python&logoColor=white)&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-80%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)&nbsp;
![Kotlin](https://img.shields.io/badge/Kotlin-75%25-7F52FF?style=flat-square&logo=kotlin&logoColor=white)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-70%25-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frameworks & Backends**

![Django](https://img.shields.io/badge/Django-85%25-092E20?style=flat-square&logo=django&logoColor=white)&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-80%25-009688?style=flat-square&logo=fastapi&logoColor=white)&nbsp;
![React](https://img.shields.io/badge/React-75%25-61DAFB?style=flat-square&logo=react&logoColor=black)&nbsp;
![Flask](https://img.shields.io/badge/Flask-80%25-000000?style=flat-square&logo=flask&logoColor=white)

**AI / ML**

![AI/ML](https://img.shields.io/badge/AI%2FML-70%25-FF6B6B?style=flat-square&logo=openai&logoColor=white)&nbsp;
![LLMs](https://img.shields.io/badge/LLMs_%26_RAG-65%25-7C3AED?style=flat-square&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   GITHUB STATS                        -->
<!-- ═══════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AshishCherian15&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F7FF&icon_color=FF6EC7&text_color=ffffff" height="160" alt="GitHub Stats"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AshishCherian15&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F7FF&text_color=ffffff" height="160" alt="Top Languages"/>

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=AshishCherian15&theme=tokyo-night&bg_color=0d1117&color=00F7FF&line=FF6EC7&point=ffffff&hide_border=true)](https://github.com/AshishCherian15)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--               CURRENTLY BUILDING                      -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🚧 Currently Building

```yaml
🤖 AI-powered Android Assistant   →  Jetpack Compose + Gemini API
🌐 Portfolio V2 with CMS          →  Next.js + Supabase
📦 SaaS Logistics Dashboard       →  React + FastAPI + PostgreSQL
```

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                 DEV QUOTES                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## ✍️ Dev Quotes

<div align="center">

> *"Talk is cheap. Show me the code."*
>
> **— Linus Torvalds**

<br/>

> *"Any fool can write code that a computer can understand.*
> *Good programmers write code that humans can understand."*
>
> **— Martin Fowler**

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=800&color=00F7FF&center=true&vCenter=true&width=620&lines=Talk+is+cheap.+Show+me+the+code.;Write+code+humans+can+understand.;Build+things+that+matter.+%F0%9F%9A%80" alt="Dev quotes typing" />

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    FOOTER                             -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

**Thanks for stopping by! 👋**

*If you found something useful, consider ⭐ starring a repo — it means a lot!*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashish-cherian-158b49356)
[![Portfolio](https://img.shields.io/badge/See_My_Work-000000?style=for-the-badge&logo=firefox&logoColor=orange)](https://portfolio-green-nine-18.vercel.app)

</div>
