# Calculator

A Java Swing calculator application that performs basic arithmetic operations with a graphical keypad-style interface.

## Features

- Addition, subtraction, multiplication, and division
- Clear and display state management
- Numeric button input and decimal support
- Uses a separate service layer for calculation logic

## Files

- `CalculatorApp.java` — application entry point
- `gui/CalculatorGui.java` — Swing UI layout and button handling
- `service/CalculatorService.java` — calculation business logic
- `constants/CommonConstants.java` — shared UI labels and constants

## Run

```powershell
cd Calculator
javac -d out src\constants\*.java src\service\*.java src\gui\*.java src\CalculatorApp.java
java -cp out CalculatorApp
```

No external libraries are required; the app runs on Java SE with Swing.