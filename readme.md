# TimeMaestro - Customizable Countdown Timer App

**TimeMaestro** is a JavaFX desktop application that lets users create, manage, and customize multiple countdown timers. With features like custom actions upon completion, color-coded timers, and history tracking, TimeMaestro is designed for flexible time management, making it ideal for tasks, study sessions, or even workouts.

## Features

- **Multi-Timer Support**: Create and run multiple timers simultaneously.
- **Custom Actions**: Configure custom actions (e.g., play sound, display message, open a file) to be triggered when a timer ends.
- **Timer Customization**:
    - Add labels and assign colors for easy identification.
    - Set custom durations for each timer.
- **Save and Load**: Save timer configurations and load them later for recurring tasks.
- **History and Statistics**: Track the number of completed timers and get statistics like total time tracked.
- **Notifications**: Receive alerts when timers finish with customizable notifications.
- **Compact Mode**: Minimal mode that displays only active timers in a streamlined interface.

## Screenshots

*Include screenshots here to demonstrate the UI and key features.*

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/TimeMaestro.git
2. **Open in your preferred IDE** (e.g., IntelliJ IDEA or Eclipse) and ensure that you have JavaFX set up:
    - Install the required JavaFX dependencies.
    - Configure your project to use JavaFX libraries (add JavaFX SDK to your project settings).

3. **Build and Run**:
    - Compile the project and run the `Main` class to start the application.

## Prerequisites

- **Java 11+**: Ensure that you have the latest version of Java installed.
- **JavaFX**: The project requires JavaFX for building the user interface.
    - You can download JavaFX from [OpenJFX](https://openjfx.io/).

## Project Structure

- **Model**: Manages timer data and logic (e.g., creating, starting, stopping timers).
- **View**: Contains JavaFX FXML files for the UI layout.
- **Controller**: Handles the user interaction between the model and the view.

### Main Components:
- `Timer`: The class representing an individual countdown timer.
- `TimerManager`: Manages all active timers and handles events like starting, pausing, and completing timers.
- `MainController`: Controls the primary view, handling the addition and customization of timers.

## Roadmap

- Add more customization for timer actions (e.g., integrating with other apps).
- Include export options for timer history and statistics.
- Add different notification styles and themes for the app.
- Add support for recurring timers.

## Contribution

Feel free to submit issues, fork the repository, or make pull requests. Contributions to improve TimeMaestro are welcome!

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
