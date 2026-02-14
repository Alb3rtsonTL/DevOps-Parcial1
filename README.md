# DevOps Parcial 1 · CI/CD Deploy [![web](https://img.shields.io/badge/web-blue)](https://github.com/Alb3rtsonTL/DevOps-Parcial1)  

![Info](https://img.shields.io/badge/type-Practice-white) ![CI](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-blue)  ![Deploy](https://img.shields.io/badge/Deploy-Surge.sh-brightgreen)  ![Uptime](https://img.shields.io/badge/uptime-100%25-brightgreen) [![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  [![Versión](https://img.shields.io/badge/Versi%C3%B3n-1.1-brightgreen)](https://github.com/Alb3rtsonTL/DevOps-Parcial1)  

<img src="/img/preview.png" alt="Preview del proyecto"><br>

---

## 📑 Descripción

**DevOps Parcial 1** es una práctica académica de la Electiva DevOps que implementa **Integración Continua y Despliegue Continuo (CI/CD)** usando **GitHub Actions** y **Surge.sh**.

El proyecto consiste en una página web estática basada en el template original y adaptada para demostrar el flujo completo de despliegue automático.

Cada vez que se hace **push en la rama `main`**, el sitio se despliega automáticamente en:

👉 **https://cicd-devops-parcial1.surge.sh**

La rama **`dev`** se usa para desarrollo y pruebas antes de hacer merge a `main`.

---

## 🛠 Tecnologías Utilizadas

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://es.wikipedia.org/wiki/HTML5)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://es.wikipedia.org/wiki/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://es.wikipedia.org/wiki/JavaScript)
[![GitHub Actions (CI/CD)](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://docs.github.com/en/actions)
[![Surge.sh (Deploy)](https://img.shields.io/badge/Surge.sh-FF6B6B?style=for-the-badge&logo=surge&logoColor=white)](https://surge.sh)

---

## 🎯 Características

1. Deploy automático al hacer push en `main`.
2. Flujo de desarrollo con ramas (`dev` → `main`).
3. Integración con Surge.sh usando GitHub Actions.
4. Uso de secretos para proteger credenciales (`SURGE_TOKEN`).
5. Landing page basada en template reutilizable.

---

## 🚀 Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/Alb3rtsonTL/DevOps-Parcial1.git
cd DevOps-Parcial1
```

- **Autor:** [Alb3rtsonTL](https://github.com/Alb3rtsonTL) - Albertson Terrero López
- **Licencia:** MIT License
- **Versión:** 1.1