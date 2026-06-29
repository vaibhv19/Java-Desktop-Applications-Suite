# Paint

A Java Swing drawing application that lets users draw freehand lines and change brush color on a custom canvas.

## Features

- Draw with the mouse on a custom canvas
- Choose stroke color using a color picker
- Reset the canvas to clear drawings
- Simple UI built with Swing and SpringLayout

## Files

- `App.java` — application entry point and Swing EDT launcher
- `PaintGui.java` — window layout, buttons, and canvas panel
- `Canvas.java` — custom drawing component and mouse event handling
- `ColorPoint.java` — model object for storing point color and position

## Run

```powershell
cd Paint
javac -d out src\*.java
java -cp out App
```

The app uses only Java SE and Swing components.