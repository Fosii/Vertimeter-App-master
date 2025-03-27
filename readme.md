# Vertimeter: Jump Detection App

Vertimeter is an Android application designed to detect and track jumps. It uses sensors in your mobile device to measure jump height, landing force, and other physical parameters in real-time. The app provides an intuitive interface for users to monitor their performance and analyze their jump dynamics.

## Features

- **Real-time Jump Detection**: Accurately detect when a jump occurs using the device’s accelerometer and gyroscope.
- **Jump Metrics**: Measure jump height, force, and duration.
- **User History**: Save and track your jump statistics over time.
- **Interactive Dashboard**: Visualize your jump data with charts and graphs.
- **Export Data**: Export jump data in CSV format for further analysis.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Android Studio installed.
- A physical Android device for testing (the app uses device sensors, so it must be tested on real hardware).
- Kotlin environment set up in your project.

## Installation

### Clone the repository:
  ```bash
  git clone https://github.com/Fosii/Vertimeter-App-master.git
```

## Steps to Set Up the Project:
1. **Open the project:** Open Android Studio and select "Open an existing project". Navigate to the cloned directory and open the project.

2. **Install dependencies:** The project uses Gradle to manage dependencies. Android Studio should automatically sync the project when opened. If it doesn't, run the following command in the terminal:
   ```bash
   ./gradlew build
3. **Run the app:** Connect your Android device or use an emulator, and then run the app from Android Studio.

## Usage
1. Open the app on your Android device.
2. Press the "Start" button to begin jump detection.
3. Perform a jump and the app will detect it using the device’s sensors.
4. View your jump metrics like height, force, and time on the interactive dashboard.
5. Optionally, export your data for further analysis.

## Configuration
You can configure the following parameters in the config directory:

- Sensor Sensitivity: Adjust the sensitivity of the sensors used for detecting jumps.
- Data Refresh Rate: Set how frequently jump data is updated on the dashboard.

## Contributing
We welcome contributions! To contribute:

- Fork this repository.
- Create a new branch for your changes.
- Make your changes.
- Submit a pull request with a detailed explanation of your modifications.

## Code Style
We follow the Kotlin coding conventions. Please ensure your code follows these conventions to maintain consistency across the project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
