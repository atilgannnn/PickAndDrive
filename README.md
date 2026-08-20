# 🚗 PickAndDrive - Car Rental Platform

PickAndDrive is a production-ready, full-stack web application that allows users to browse and reserve vehicles while providing administrators with a dashboard to manage fleet operations, image assets, and user roles.

🌐 **Live Backend API:** [pickanddrive-frontend.onrender.com](https://pickanddrive-frontend.onrender.com/)  
⚡ **Live Swagger Docs:** [pickanddrive-backend.onrender.com/swagger-ui/index.html](https://pickanddrive-backend.onrender.com/swagger-ui/index.html)

---

### 📌 Key Features
* **Role-Based Access Control (RBAC):** Secure authentication and authorization using Spring Security and JWT (`ROLE_CUSTOMER`, `ROLE_ADMIN`).
* **Vehicle Fleet Management:** CRUD operations for vehicles, dynamic filtering, and reservation constraints.
* **Multipart File Upload:** Custom image upload handling supporting up to 10MB assets for high-resolution car media.
* **Containerized Deployment:** Dockerized Spring Boot service hosted on Render with connected PostgreSQL database.

---

### 🛠️ Tech Stack
* **Backend:** Java 17, Spring Boot 2.7.8, Spring Security, JWT, JPA / Hibernate
* **Database:** PostgreSQL
* **DevOps & Hosting:** Docker, Render Cloud
