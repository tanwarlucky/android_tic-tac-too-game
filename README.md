# Tic-Tac-Toe Android App (Java)

A sleek, lightweight, and modern **Tic-Tac-Toe** game application built for Android using pure Java. This project demonstrates clean object-oriented program logic, explicit state management, and custom button interactions inside Android Studio.

## 📱 Features
* **Two-Player Offline Mode:** Classic pass-and-play mechanics on a single screen.
* **Interactive Grid Layout:** Fast-rendering 3x3 layout built with customized native widgets.
* **Real-time Status Banner:** Dynamically shifts text to announce current turns, match-winning plays, or a stalemate draw.
* **Instant Reset System:** One-tap button to clear the matrix arrays and restart the match immediately.
* **Responsive Visual Feedback:** Buttons display crisp, instantaneous visual updates when players tap them.

## 🛠️ Tech Stack & Architecture
* **IDE:** Android Studio
* **Language:** Java (JDK 17 / JDK 21 optimized)
* **UI Engine:** Android XML (ConstraintLayout & native Widgets)
* **Design Standards:** Android AppCompat Components

## 🚀 Getting Started

### Prerequisites
Make sure your development environment matches or exceeds these requirements:
* Android Studio (Ladybug or newer)
* Android SDK (API Level 23 Minimum Requirement)
* Active Gradle build tools configuration

### Installation & Setup
1. Clone this repository directly onto your system:
   ```bash
   git clone https://github.com
   ```
2. Open **Android Studio**.
3. Choose **File > Open** and select the cloned project folder directory.
4. Allow Android Studio to sync the project libraries with Gradle files.
5. Connect your physical phone (or configure an emulator instance).
6. Click the green **Run (Play)** button in the top toolbar to build and deploy.

## 📁 Java Project Architecture
```text
app/
 └── src/
      └── main/
           ├── java/com/myapp/tictactoe/        
           │    └── MainActivity.java           # Controls Java matrix arrays & grid listeners
           └── res/
                ├── layout/
                │    └── activity_main.xml      # Core UI layout design grid
                └── drawable/
                     └── custom_button_shape.xml # Holds your custom button corner geometries
```

## 🧠 Java Logic Breakdown
The backend utilizes simple, high-performance logic arrays to evaluate game parameters:
* **State Array:** A primitive 1D integer or char array representing the 9 individual grid tiles.
* **Winning Combinations:** A 2D matrix storing all 8 index possibilities for three-in-a-row paths (horizontal, vertical, diagonal).
* **Reset Routine:** Re-initializes the state variables and sets button texts to blank space strings during runtime without resetting the Activity lifecycle.

## 🤝 Contributing
Contributions make the open-source community an amazing place to learn, inspire, and create. 
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.
