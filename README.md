# 🎓 Student Hub Portal

**Student Hub Portal** is a functional web application prototype developed for the **IMS566 – Advanced Web Design Development and Content Management** individual project.
The portal serves as a centralized digital workspace for university students to manage their academic journey.

It emphasizes a **professional UI/UX**, enabling students to monitor academic performance (CGPA), manage course enrollments, track exam results, and stay informed with real-time campus announcements.
This project demonstrates advanced front-end techniques, responsive design, and simulated content management systems.

---

## 🚀 Project Features

The application consists of **8 distinct pages**, exceeding the minimum project requirements to deliver a comprehensive student experience:

### 🏠 Landing Page

* **`index.html`**
* Professional hero section
* Modern navigation layout

### 🔐 Authentication System

* **Login Page (`login.html`)**

  * Form validation
  * Error feedback for incorrect credentials
* **Registration Page (`register.html`)**

  * Simulated new account creation
  * User data stored in `localStorage`

### 📊 Academic Dashboard

* **`dashboard.html`**
* Summary cards for:

  * CGPA
  * Credit Hours
  * Attendance
* Interactive GPA performance bar chart

### 📚 Data View Pages

* **Course List (`courses.html`)**

  * Structured table of current semester enrollments
* **Exam Results (`results.html`)**

  * Grade distribution grid across subjects

### 📰 Campus News

* **`announcements.html`**
* Structured announcement system
* Demonstrates content organization and metadata management

### 👤 Student Profile

* **`profile.html`**
* Personalized student information
* Portal settings overview

---

## 🧪 Login Testing Instructions

The application uses **simulated authentication** with session guarding to protect academic data.

### Option 1: Hardcoded Credentials

1. Navigate to the **Login Page**
2. Enter the following:

   * **Username:** `admin`
   * **Password:** `1234`
3. Click **Login to Hub**

### Option 2: Register a New Account

1. Navigate to the **Register Page**
2. Create a custom username and password
3. Credentials are saved in the browser’s `localStorage`
4. Return to the **Login Page** and log in with your new credentials

> 🔒 **Note:** Protected pages (Dashboard, Courses, Results, Announcements, and Profile) are secured.
> Attempting direct access via URL without logging in will redirect users to the login page.

---

## 🛠️ Frameworks & Libraries Used

* **CSS Framework:** Tailwind CSS
  *(Utility-first framework for responsive layouts)*
* **Data Visualization:** Chart.js
  *(Interactive academic performance graphs)*
* **Iconography:** Lucide Icons
  *(Clean and professional UI icons)*
* **Typography:** Plus Jakarta Sans
  *(Modern geometric sans-serif font)*
* **State Management:** Vanilla JavaScript

  * `sessionStorage` for active user sessions
  * `localStorage` for user account persistence

---

## 🌐 Deployment

* **Live Website (GitHub Pages):**
  👉 *https://natashaanuar567.github.io/STUDENT-HUB/*

* **GitHub Repository:**
  👉 *https://github.com/Natashaanuar567/STUDENT-HUB*

---

## 🎓 Course Information

* **Course:** IMS566 – Advanced Web Design Development and Content Management
* **Developer:** *NURUL NATASHA BINTI HAIRUL ANUAR*
* **Student ID:** *2025180917*
* **Email:** *tashaanuarrrr@gmail.com*
* **Faculty:** Faculty of Information Management, UiTM