# Student_Grade_Tracker
# 📌 JavaFX UI Prototype

## 🚀 Project Overview
This is the initial JavaFX UI prototype for our project. The focus is on setting up a structured JavaFX application with basic navigation and UI elements. No functionality has been implemented yet.

## 📂 Project Structure
```
📦 javafx-ui-prototype
 ┣ 📂 src
 ┃ ┣ 📂 main
 ┃ ┃ ┣ 📂 java
 ┃ ┃ ┃ ┣ 📂 com.example.ui
 ┃ ┃ ┃ ┃ ┣ 📜 Main.java  # Application entry point
 ┃ ┃ ┃ ┃ ┣ 📜 SceneManager.java  # Handles navigation between screens
 ┃ ┃ ┣ 📂 resources
 ┃ ┃ ┃ ┣ 📂 fxml
 ┃ ┃ ┃ ┃ ┣ 📜 Dashboard.fxml  # Dashboard UI
 ┃ ┃ ┃ ┃ ┣ 📜 CoursePage.fxml  # Course Page UI
 ┃ ┃ ┃ ┃ ┣ 📜 GradeEntry.fxml  # Grade Entry Page UI
 ┃ ┃ ┃ ┣ 📂 css
 ┃ ┃ ┃ ┃ ┣ 📜 styles.css  # Material Design UI styles
 ┣ 📜 README.md  # Project documentation
 ┣ 📜 .gitignore  # Git ignore file
 ┣ 📜 pom.xml / build.gradle  # JavaFX dependencies (Maven/Gradle)
```

## 📌 Team Responsibilities
### **Rahith (Project Lead & Backend Dev)**
- Set up JavaFX project structure in GitHub.
- Implement basic navigation between screens.

### **Member 2 (UI Designer & Frontend Dev)**
- Create `FXML` layouts for Dashboard, Course Page, and Grade Entry Page.
- Apply Material Design CSS for UI consistency.

### **Member 3 (Testing & Analytics)**
- Review UI for flow consistency and missing components.
- Suggest potential UI validation cases.

### **Member 4 (Documentation Lead)**
- Write UI documentation describing each page and interaction.

## 📋 Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/javafx-ui-prototype.git
   cd javafx-ui-prototype
   ```
2. Open the project in your IDE (IntelliJ IDEA recommended).
3. Install JavaFX SDK (if not already installed).
4. Run the project:
   ```bash
   mvn javafx:run  # For Maven
   # OR
   gradle run  # For Gradle
   ```

## 📌 UI Screens
### **Dashboard Page**
- Displays course overview and recent grades.
- Navigation to Course Page and Grade Entry Page.

### **Course Page**
- Lists enrolled courses with details.
- Option to navigate to specific course details.

### **Grade Entry Page**
- Form for entering student grades.
- Basic input validation (to be implemented later).

## 🎨 UI Styling
- Material Design-inspired CSS (`styles.css`).
- Responsive layout for different screen sizes.

## 📌 Next Steps
- Implement UI interactivity (button actions, input validation).
- Connect frontend with backend logic.
- Conduct user testing and refine UI elements.

## 📜 License
This project is open-source and licensed under the MIT License.

---

