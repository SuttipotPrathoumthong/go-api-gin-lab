# Student API with Gin & SQLite
REST API สำหรับจัดการข้อมูลนักเรียน พัฒนาด้วยภาษา Go โดยใช้ Gin Framework และ SQLite ตามโครงสร้าง Layered Architecture
---
## How to run the project

### 1. Clone repository
```bash
git clone https://github.com/SuttipotPrathoumthong/go-api-gin-lab.git
cd go-api-gin-lab
```
### 2. ติดตั้ง Dependencies ด้วยการเปิด Terminal ในโฟลเดอร์โปรเจกต์แล้วรันคำสั่ง:
```bash
go mod tidy
```
### 3. Run Project ด้วยคำสั่ง
```bash
go run main.go
```
ระบบจะเริ่มต้นทำงานที่พอร์ต 8080 โดยอัตโนมัติ
---
## Available API Endpoints
### GET /students ดึงข้อมูลนักเรียนทั้งหมด
### GET /students/:id ดึงข้อมูลนักเรียนรายคน
### POST /students เพิ่มข้อมูลนักเรียนใหม่ (id, name, gpa ห้ามว่าง และ gpa ต้องอยู่ระหว่าง 0-4)
### PUT /students/:id อัปเดตข้อมูลนักเรียนรายคน (name, major, gpa ห้ามว่าง และ gpa ต้องอยู่ระหว่าง 0-4)
### DELETE /students/:id ลบข้อมูลนักเรียนรายคน
