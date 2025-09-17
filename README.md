# 🚀 BootMail AI

An AI-powered Gmail extension that seamlessly integrates an intelligent backend with the Gmail UI to generate instant, context-aware email replies.

<br>

## ✨ Overview

**BootMail AI** is a full-stack, AI-powered email assistant developed as a browser extension. It seamlessly integrates a custom **Spring Boot backend** with the **Gmail UI**, enabling users to generate instant, context-aware email replies with the click of a button. 

The project demonstrates a comprehensive understanding of client-side and server-side development by:

* **Engineering a RESTful API** in Java with Spring Boot to process user requests and communicate with a powerful AI model.
* **Developing a dynamic content script** to inject a custom "AI Reply" button directly into the Gmail compose toolbar, ensuring a native user experience.
* **Implementing robust CORS security** and **browser extension permissions** to allow for secure cross-origin communication between the extension and the backend server.

This project showcases a hands-on application of modern web technologies to solve a practical problem, highlighting skills in API design, full-stack integration, and browser extension development.
-----

## 💡 Key Features

  - **Seamless UI Integration**: A custom "AI Reply" button is injected directly into the Gmail's native interface.
  - **Intelligent Context Analysis**: The extension extracts the email's content and sends it to the backend for accurate reply generation.
  - **RESTful API**: A clean and robust API handles requests and returns a generated response.
  - **CORS Security**: Properly configured to allow secure communication between the browser extension and the backend server.

-----

## 🛠️ Technologies Used

### Frontend (Browser Extension)

  - **JavaScript**: For DOM manipulation, event handling, and API calls.
  - **HTML/CSS**: To create the extension's UI components.
  - **Chrome Extension API**: For injecting the content script into the Gmail page.

### Backend (API)

  - **Java**: The core programming language.
  - **Spring Boot**: A powerful framework for building a production-ready, standalone API.
  - **Maven**: For dependency management and building the project.
  - **REST API**: The architectural style for communication.

-----

## 📦 Repository Structure

The project is split into two main directories for clear separation of concerns.

```
/BootMail-AI/
├── frontend/             # All code for the browser extension
│   ├── manifest.json
│   ├── content.js
│   └── ...
│
└── backend/              # All code for the Spring Boot application
    ├── src/
    ├── pom.xml
    └── ...
```

-----

## 🚀 Getting Started

To get the project up and running locally, follow these simple steps for both the backend and frontend.

### Prerequisites

  - **Java 17+** installed.
  - **Maven** installed.
  - **Node.js** installed (if you need to use npm commands).

### Backend Setup

1.  Navigate to the `backend` directory in your terminal:
    ```bash
    cd backend
    ```
2.  Build the project using Maven:
    ```bash
    mvn clean install
    ```
3.  Run the application from the `target` directory:
    ```bash
    java -jar target/email-generator-app-0.0.1-SNAPSHOT.jar
    ```
    Your API will now be running on `http://localhost:8080`.

### Frontend Setup

1.  Open your browser (e.g., Chrome, Brave).
2.  Navigate to the extensions page by typing `chrome://extensions` in the address bar.
3.  Enable **Developer mode** in the top-right corner.
4.  Click on **"Load unpacked"** and select the `frontend` directory from your cloned repository.
5.  The **BootMail AI** extension icon will appear in your toolbar.

Now, open Gmail and start a new compose window to see the "AI Reply" button in action\!

-----

## 🤝 Contribution

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

-----

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
