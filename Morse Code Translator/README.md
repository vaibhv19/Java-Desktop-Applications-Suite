# Morse Code Translator 🔤➡️📻

A Java Swing application that converts typed text into Morse code in real time and plays the translated output as audio.

## Features

- Real-time text-to-Morse translation
- Output displayed in a scrollable text area
- Plays Morse code tones using Java audio APIs
- Uses keyboard input listeners for live updates

## Files

- `App.java` — application entry point and Swing EDT launcher
- `MorseCodeController.java` — Morse code translation and audio playback logic
- `MorseCodeTranslatorGUI.java` — UI construction, input handling, and result display

## Run

```powershell
cd "Morse Code Translator"
javac -d out src\*.java
java -cp out App
```

Requires Java SE; no additional libraries are needed.