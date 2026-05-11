# Snake_GAME

Simple Java Swing Snake game.

Build and run:

```bash
# from repository root
mkdir -p out
javac -d out src/Game.java
java -cp out Game
```

If your editor (VS Code) shows red error underlines for Swing/AWT classes even though the project compiles and runs, do one of the following:

- Reload the VS Code window (Command Palette: Developer: Reload Window).
- Ensure the Java Extension Pack is installed (Language Support for Java, Debugger for Java, etc.).
- Set workspace JDK in `.vscode/settings.json` to your JDK path. Example:

```json
{
  "java.home": "/Library/Java/JavaVirtualMachines/jdk-24.jdk/Contents/Home"
}
```

If you want, I can add a `build` task and a launch configuration for VS Code.
