# Java Mini Projects

A collection of small Java desktop applications built with **Java SE** and **Swing**. Each project demonstrates GUI development, event-driven programming, and core object-oriented design.

## Included Applications

- **Calculator**
  - Basic arithmetic operations: addition, subtraction, multiplication, division
  - Includes a Swing-based button interface and display
- **Tic Tac Toe**
  - Two-player board game with win and draw detection
  - Score tracking and reset support
- **Paint**
  - Freehand drawing using mouse input
  - Color selection and canvas reset
- **Morse Code Translator**
  - Translates typed text into Morse code in real time
  - Plays Morse code audio tones using Java sound APIs
- **To Do List**
  - Add and manage tasks in a simple task panel
  - Uses custom components and a scrollable UI

## Repository Structure

```
Java Mini Projects/
├── Calculator/
│   ├── src/
│   │   ├── CalculatorApp.java
│   │   ├── constants/CommonConstants.java
│   │   ├── gui/CalculatorGui.java
│   │   └── service/CalculatorService.java
│   └── README.md
├── Morse Code Translator/
│   ├── src/
│   │   ├── App.java
│   │   ├── MorseCodeController.java
│   │   └── MorseCodeTranslatorGUI.java
│   └── README.md
├── Paint/
│   ├── src/
│   │   ├── App.java
│   │   ├── Canvas.java
│   │   ├── ColorPoint.java
│   │   └── PaintGui.java
│   └── README.md
├── Tic Tac Toe/
│   ├── src/
│   │   ├── App.java
│   │   ├── CommonConstants.java
│   │   └── TicTacToeGui.java
│   └── README.md
├── To Do List/
│   ├── src/
│   │   ├── App.java
│   │   ├── CommonConstants.java
│   │   ├── TaskComponent.java
│   │   ├── ToDoList.java
│   │   ├── ToDoListGui.java
│   │   └── resources/
│   └── README
└── README.md
```

## How to Run

Each app is self-contained in its own folder. Use the Java compiler and runtime from the command line, or import the folder into an IDE such as IntelliJ IDEA or Eclipse.

### Run from Command Line

1. Open a terminal in the repository root.
2. Change into the app folder.
3. Compile sources.
4. Run the app.

Example for **Tic Tac Toe**:

```powershell
cd "Tic Tac Toe"
javac -d out src\*.java
java -cp out App
```

Example for **Paint**:

```powershell
cd Paint
javac -d out src\*.java
java -cp out App
```

Example for **Morse Code Translator**:

```powershell
cd "Morse Code Translator"
javac -d out src\*.java
java -cp out App
```

Example for **Calculator** (package-based structure):

```powershell
cd Calculator
javac -d out src\constants\CommonConstants.java src\service\CalculatorService.java src\gui\CalculatorGui.java src\CalculatorApp.java
java -cp out CalculatorApp
```

Example for **To Do List**:

```powershell
cd "To Do List"
javac -d out src\*.java
java -cp out App
```

> Note: The `To Do List` app includes a custom font file under `resources/`. If you run from a terminal, ensure the `resources` folder is available on the classpath or use an IDE that includes resources automatically.

## What You Can Learn

- Building desktop GUIs with Java Swing
- Connecting UI controls to application logic
- Managing application state and user input
- Working with Java collections and custom components
- Handling mouse, keyboard, and button events
- Playing sound output with Java audio APIs

## Recommended Improvements

- Add persistent storage for the To Do List
- Export Paint drawings or support different brush sizes
- Add undo/redo for Paint and To Do List tasks
- Improve Tic Tac Toe AI or add single-player mode
- Migrate these apps to JavaFX for a modern UI

## Contribution

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## Author

**Vaibhav Gupta**


