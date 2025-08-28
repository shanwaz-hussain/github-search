# GitHub Repository Search – Full Stack Mini App

---

## 📖 What is this project about?

A full-stack web app that lets users search for GitHub repositories by keyword, fetches real-time data from the GitHub API via a custom Spring Boot backend, stores the results in a MySQL database, and displays everything in a neat, interactive dashboard.

---

## 🔗 Project Flow

1. **Frontend (React):**  
   The user enters a keyword and clicks Search.

2. **Spring Boot API (Backend):**  
   The keyword is sent to the backend. The backend uses GitHub's API to fetch repositories for that keyword.

3. **Database (MySQL):**  
   The fetched repositories are stored in a MySQL database (using Railway for cloud/MySQL hosting).

4. **Dashboard Display:**  
   The frontend fetches and displays all stored repositories in a paginated, filterable table.

---

## 🌐 Live Demo and Code

- **Live App:** [https://github-search-shanwaz.vercel.app/](https://github-search-shanwaz.vercel.app/)
- **Frontend Source:** [github-search-frontend](https://github.com/shanwaz-hussain/github-search-frontend)
- **Backend Source:** [githubrepoapi](https://github.com/shanwaz-hussain/githubrepoapi)

---

## 🖼️ Screenshots

## Home & Search 
<img width="1920" height="1020" alt="Screenshot 2025-08-28 204620" src="https://github.com/user-attachments/assets/4289deb7-fee3-4e9d-aa83-a8d3e68a52ec" />

## Results Dashboard
<img width="1920" height="1020" alt="Screenshot 2025-08-28 204720" src="https://github.com/user-attachments/assets/8ea4b62c-1f99-43b9-bd6b-daedae059b21" />

## Database (MySQL in Railway)
<img width="1085" height="583" alt="Screenshot 2025-08-28 204900" src="https://github.com/user-attachments/assets/e0cbd7b3-d651-4bbb-acb8-7b9bc2c5e403" />

---

## 🗝️ How to run locally

1. **Backend**
    - Set MySQL credentials in `application.properties`
    - Run with: `./mvnw spring-boot:run` or from your IDE
    - MySQL must have a database named `githubrepo_db`

2. **Frontend**
    - `npm install` then `npm start` in frontend folder
    - Update backend API URL if necessary (`src/RepoSearch.js` or similar)

3. **Database**
    - Can be Railway/cloud or local MySQL

---

## 📋 Credits

- Uses [GitHub REST API](https://docs.github.com/en/rest)
- Bonus: Responsive, modular, clean code—meets assignment and production standards

---

