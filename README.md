# Rule-Based Chatbot 🌍

A Spring Boot application that implements a simple **rule-based chatbot**.  
The chatbot answers questions about countries’ **capitals, national animals, and national flowers**, while remembering the selected country during a conversation (session management).  

This project demonstrates **prompt engineering** and the use of **Amazon Q Developer** to accelerate software development.

---

## 🚀 Features
- Rule-based chatbot logic with predictable responses.
- Provides information about:
  - Capital city
  - National animal
  - National flower
- Remembers the selected country across conversation (session persistence).
- Simple **web-based interface** built with Thymeleaf and JavaScript.
- Backend powered by **Spring Boot**.
- Country data stored in **JSON** and managed via a loader service.

---

## 🛠️ Technologies Used
- **Java (Spring Boot)**
- **Thymeleaf** for UI templates
- **JavaScript + AJAX** for dynamic chat updates
- **Amazon Q Developer** for efficiency, help with code completion and & productivity
- **JSON file storage** for country facts

---

## 📂 Project Structure
- `CountryInfo.java` – Data model for country facts  
- `CountryDataLoader.java` – Loads data from JSON into a HashMap  
- `ChatbotService.java` – Service layer between logic and data  
- `RuleBasedEngine.java` – Core chatbot logic  
- `ConversationContext.java` – Manages session state  
- `ChatbotController.java` – Handles HTTP requests and chat endpoint  
- `HomeController.java` – Routes to main page  
- `index.html` – Chatbot web interface  

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AbhishekRajGhimire/rule-based-chatbot.git
   cd rule-based-chatbot/chatbot
2. Build and run with Maven/Gradle:
   ./mvnw spring-boot:run          or,
   ./gradlew bootRun
3. Open your browser and go to:
   http://localhost:8080
