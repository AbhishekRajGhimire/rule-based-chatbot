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







the interface(the start)

<img width="2491" height="1357" alt="Screenshot 2026-01-16 041533" src="https://github.com/user-attachments/assets/ea16dc1d-25d5-4ac1-baef-748dc1328b1e" />

the first interaction

<img width="2483" height="1353" alt="Screenshot 2026-01-16 042127" src="https://github.com/user-attachments/assets/9352f550-7892-4fa6-a218-d4f47acafd65" />

When asked further

<img width="2502" height="1354" alt="Screenshot 2026-01-16 042304" src="https://github.com/user-attachments/assets/77cf8c2d-a736-4139-ad3f-e332b0408fc6" />

when given the wrong instruction

<img width="2510" height="1329" alt="Screenshot 2026-01-16 042419" src="https://github.com/user-attachments/assets/59315e3c-96d2-44aa-a9ab-5d27ef40ac47" />

Clearing the chat

<img width="2501" height="1335" alt="Screenshot 2026-01-16 042610" src="https://github.com/user-attachments/assets/fa95a1bc-15ff-4906-9a21-3ba5b78210a4" />

