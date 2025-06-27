# 🌍 Dostrip – Smart Travel Planner

Dostrip is a web-based smart travel advisor that uses intelligent tools and user preference data to deliver personalized travel recommendations. The system integrates authentication, cloud storage, and ML-based suggestion tools to help users plan trips with safety, comfort, and relevance.


## 📝 Abstract

Dostrip is an intelligent travel planning app that assists users in choosing destinations, activities, and accommodations based on their interests, budget, time, and preferences. Unlike other travel tools, Dostrip offers a **fully personalized** experience through a dynamic questionnaire and intelligent recommendation engine. It ensures travelers have access to smart, filtered suggestions and reviews while providing a user-friendly interface.

## 🌐 Technology Stack

| Area           | Technologies Used                                   |
|----------------|-----------------------------------------------------|
| Frontend       | HTML, CSS, JavaScript, React                        |
| Backend        | Firebase (Auth + Firestore), Recommendation Engine  |
| Hosting        | Netlify                                             |
| Auth           | Google Authentication (Firebase)                   |
| Tools          | Jira, Microsoft Teams, GitHub, VS Code              |
| Design         | Figma, Draw.io                                      |
| Documentation  | Overleaf                                            |


## 🏗️ Architecture & Design

- **Client-Server Model**: React frontend, Firebase backend
- **Cloud-hosted**: Real-time database & authentication via Firebase
- **ML Integration**: Third-party tool + custom logic for recommendation generation
- **Secure Login**: Google OAuth
- **MVC & Layered Architecture Patterns** applied for modular, testable code

> 📊 See architecture diagram, use case, activity, and sequence diagrams in the documentation or Appendix A.


## ✨ Key Features

- 🧾 **User Registration/Login** via Google Authentication
- 🧠 **Questionnaire-Based Input** for travel preferences
- 🧳 **Personalized Travel Recommendations** (places, activities, stays)
- 🔎 **Filtering Options** for price, activity type, and more
- 📝 **Review System**: Read & write reviews for destinations
- 🔒 **Logout & Session Management**


## 🧠 Intelligent Recommendation System

The heart of Dostrip is its smart suggestion engine:
- 📥 Gathers user preferences (weather, location, budget, traits, etc.)
- 🤖 Uses NLP and ML-based algorithms to analyze inputs
- 📊 Suggests custom travel plans based on real-time and static data
- 🧩 Combined third-party tools + own data models for accuracy


## 🧪 Functional & Non-Functional Requirements

### ✅ Functional Requirements:
- User Registration & Login
- Questionnaire Submission
- Travel Recommendation Display
- Filtering by price/activity
- User Reviews (read/write)
- Secure Logout

### 🚀 Non-Functional Requirements:
- **Usability**: Clean and responsive UI
- **Performance**: Fast responses and data load
- **Availability**: Accessible from any modern browser
- **Reliability**: Accurate and consistent results


## 📊 Software Metrics

| Component                   | LOC  | Unit Tests | Granularity Level |
|----------------------------|------|------------|-------------------|
| Signup & Auth              | 56   | 8          | Class/Component   |
| Login                      | 106  | 7          | Class/Component   |
| Homepage + Navigation      | 88   | 7          | Class/Component   |
| Questionnaire              | 92   | 6          | Class/Component   |
| Form Validation            | 38   | 6          | Class/Component   |

> 🧪 Unit tests written for React components.  
> 📸 Test snapshots included in Appendix A.


## 🧱 Design Patterns Used

### ✅ MVC Architecture:
- **Model**: Firebase database, Recommendation Engine
- **View**: React components for UI
- **Controller**: Auth logic, questionnaire handler, filtering, etc.

### ✅ Layered Architecture:
- **Presentation Layer**: React
- **Business Logic**: Questionnaire handler, recommendation logic
- **Data Access Layer**: Firebase + ML Tool


## 📈 Agile Sprints Overview

### 🏁 Sprint 1:
- ✔ Frontend for Sign-up/Login
- ✔ Questionnaire UI
- ✔ Forgot Password
- ✔ Homepage

### 🏁 Sprint 2:
- ✔ Recommendation System Backend
- ✔ Admin Console Setup
- ✔ Filtering Feature (Planned)
- ✔ Connecting Firebase with Questionnaire



