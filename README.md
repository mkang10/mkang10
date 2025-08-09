<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="300" viewBox="0 0 1200 300" preserveAspectRatio="xMidYMid slice" role="img" aria-label="Tech Banner">
  <defs>
    <!-- Vibrant animated gradient background -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0a0f24">
        <animate attributeName="stop-color" dur="6s" repeatCount="indefinite" values="#0a0f24;#001529;#071847;#0a0f24" />
      </stop>
      <stop offset="50%" stop-color="#07102a">
        <animate attributeName="stop-color" dur="6s" repeatCount="indefinite" values="#07102a;#0f1f3a;#01243a;#07102a" />
      </stop>
      <stop offset="100%" stop-color="#001529">
        <animate attributeName="stop-color" dur="6s" repeatCount="indefinite" values="#001529;#08203b;#07102a;#001529" />
      </stop>
    </linearGradient>

    <!-- Moving highlight for text -->
    <linearGradient id="textLift" x1="-100%" y1="0%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00ffd5" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00b3ff" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7b61ff" stop-opacity="0"/>
      <animate attributeName="x1" from="-100%" to="100%" dur="5s" repeatCount="indefinite" />
      <animate attributeName="x2" from="0%" to="200%" dur="5s" repeatCount="indefinite" />
    </linearGradient>

    <!-- Glow filter -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bgGrad)"/>

  <!-- Animated circuit lines -->
  <g stroke="#00ffd5" stroke-opacity="0.1" stroke-width="2">
    <line x1="-300" y1="50" x2="1500" y2="50">
      <animate attributeName="x1" from="-300" to="1500" dur="12s" repeatCount="indefinite" />
      <animate attributeName="x2" from="0" to="1800" dur="12s" repeatCount="indefinite" />
    </line>
    <line x1="1500" y1="250" x2="-300" y2="250" stroke="#7b61ff">
      <animate attributeName="x1" from="1500" to="-300" dur="16s" repeatCount="indefinite" />
      <animate attributeName="x2" from="1800" to="0" dur="16s" repeatCount="indefinite" />
    </line>
  </g>

  <!-- Main Text -->
  <text x="50" y="140" font-family="'Segoe UI', sans-serif" font-size="56" font-weight="700" fill="white" filter="url(#glow)">Nguyễn Mạnh Cường</text>
  <text x="50" y="190" font-family="'Segoe UI', sans-serif" font-size="26" font-weight="500" fill="url(#textLift)">Web Developer · Full-stack · Next.js · ASP.NET Core</text>

  <!-- Decorative glowing dots -->
  <circle cx="1150" cy="60" r="6" fill="#00ffd5">
    <animate attributeName="r" values="6;10;6" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="1100" cy="240" r="4" fill="#7b61ff">
    <animate attributeName="r" values="4;8;4" dur="6s" repeatCount="indefinite" />
  </circle>
</svg>


<p align="center">
  <h1>Hi 👋, I'm Nguyễn Mạnh Cường</h1>
  <h3>🚀 Full-Stack Developer | Distributed Systems | DevOps Enthusiast</h3>
</p>

---

## 🛠 Tech Stack

### **Programming Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=fff)

### **Frameworks & Platforms**
![ReactJS](https://img.shields.io/badge/ReactJS-61DAFB?style=for-the-badge&logo=react&logoColor=000)
![NextJS](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=fff)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=fff)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=fff)
![ASP.NET MVC](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=fff)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-68217A?style=for-the-badge&logo=dotnet&logoColor=fff)

### **UI Libraries**
![MaterialUI](https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=fff)
![Bulma](https://img.shields.io/badge/Bulma-00D1B2?style=for-the-badge&logo=bulma&logoColor=fff)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=fff)

### **Databases**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=fff)
![MS SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=fff)

### **Cloud & DevOps**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=fff)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=fff)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff)
![CI/CD](https://img.shields.io/badge/CI/CD-000000?style=for-the-badge&logo=githubactions&logoColor=fff)

---



## 📫 Contact Me
📧 Email: masonkang1212@gmail.com(mailto:masonkang1212@gmail.com)  
🌐 Portfolio: https://masonkang.io.vn/(https://your-portfolio.com](https://masonkang.io.vn/)

---

<p align="center">
  <i>"Code is like humor. When you have to explain it, it’s bad."</i>
</p>
