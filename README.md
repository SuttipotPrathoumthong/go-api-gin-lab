# Student API with Gin & SQLite

Suttipot Prathoumthong 6609650699
A REST API for managing student data, developed using Go, the Gin Framework, and SQLite.

---
## How to run the project

### 1. Clone repository
```bash
git clone https://github.com/SuttipotPrathoumthong/go-api-gin-lab.git
cd go-api-gin-lab
```
### 2. Install dependencies by run the following command in project terminal:
```bash
go mod tidy
```
### 3. Run Project with the following command:
```bash
go run main.go
```
The server will start automatically on Port 8080.

---
## Available API Endpoints
* GET /students - Retrieve all student data.
* GET /students/:id - Retrieve individual student data by ID.
* POST /students - Add new student data (ID, Name, and GPA are required; GPA must be 0.00-4.00).
* PUT /students/:id - Update student data (Name, Major, and GPA are required; GPA must be 0.00-4.00).
* DELETE /students/:id - Delete a student record by ID.
