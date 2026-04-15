# Node.js & MySQL Docker Compose Application

A containerized Node.js application with MySQL database using Docker Compose - Lab 9 Project.

---

## Technologies Used

- **Node.js 18** - Application runtime
- **MySQL 8.0** - Database
- **Docker & Docker Compose** - Container orchestration

---

##  How to Run the Application

### 1. Clone the repository
```bash
git clone https://github.com/shroukallam/kubernets-app.git
cd kubernets-app


docker-compose up -d --build

http://localhost:3000

<img width="862" height="720" alt="Screenshot 2026-04-16 010520" src="https://github.com/user-attachments/assets/d7fa47ea-710d-472d-91f6-487b04747e99" />

http://localhost:3000/health
<img width="840" height="95" alt="health" src="https://github.com/user-attachments/assets/05a3a6bb-6e40-482f-b983-94753c1a3fe9" />
<img width="626" height="210" alt="image" src="https://github.com/user-attachments/assets/9302a06d-67bf-4927-9c12-12211c124702" />

http://localhost:3000/ready
<img width="850" height="65" alt="image" src="https://github.com/user-attachments/assets/b7612159-b1e9-4ca9-a18a-ada3dcaf6058" />
<img width="563" height="182" alt="image" src="https://github.com/user-attachments/assets/31e9f7ee-e03e-4e5c-a4f5-010cfe159424" />



