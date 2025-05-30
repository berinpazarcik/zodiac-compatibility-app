# Zodiac Compatibility App

This project is a Java-based application designed to evaluate the compatibility between zodiac signs using object-oriented programming principles. The app supports a graphical user interface (GUI) and a console-based interaction option.

## Features

- 🧠 OOP Concepts:
  - **Abstraction** via the `ZodiacSign` abstract class.
  - **Encapsulation** with private fields and public getter methods.
  - **Polymorphism** through multiple `CompatibilityCalculator` implementations.
  - **Inheritance** via 12 individual zodiac sign subclasses.

- 📊 Compatibility scoring system (0–100) with:
  - Best matches scoring near 100.
  - Challenging matches scoring closer to 50.
  - Friendship and professional compatibility messages also included.

- 🖥️ Graphical User Interface (GUI):
  - Built with Java Swing (`ZodiacGui.java`)
  - Dropdown selection for user and partner signs.
  - Real-time display of compatibility score and interpretation.

## How to Run

1. **Compile the Project:**
   ```bash
   javac ZodiacApp.java ZodiacGui.java
   ```

2. **Run the GUI:**
   ```bash
   java ZodiacGui
   ```

   Alternatively, to use the console version:
   ```bash
   java ZodiacApp
   ```

## File Descriptions

- `ZodiacApp.java`: Contains the core logic, zodiac sign classes, and compatibility calculations.
- `ZodiacGui.java`: Implements the GUI using Java Swing, providing user-friendly interaction.

## Example Output (Console)
```
Enter your zodiac sign: Leo
Enter partner's zodiac sign: Aries
Compatibility Score: 92
Comment: Excellent match! Full of energy and passion.
```

## Future Enhancements

- Add birthdate input to automatically determine zodiac sign.
- Expand compatibility calculations with external datasets.
- Add multilingual support.

## License

This project is for educational purposes only.

