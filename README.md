# Rupee Reader

Rupee Reader is an innovative mobile application designed to assist visually impaired individuals in identifying Indian currency notes. Leveraging TensorFlow Lite, the application utilizes machine learning models to detect and recognize various denominations of Indian currency notes. With Rupee Reader, users can receive real-time feedback on the currency notes they encounter, both in voice and text format, enabling greater independence and accessibility for visually impaired individuals.

## Features

- **Currency Detection**: Rupee Reader employs TensorFlow Lite models to accurately detect and identify Indian currency notes, including denominations ranging from ₹10 to ₹2000.
- **Voice and Text Output**: The application provides real-time feedback on the detected currency notes in both voice and text formats, allowing users to receive information audibly or through text-to-speech conversion.
- **User-Friendly Interface**: Rupee Reader features an intuitive and easy-to-use interface designed with accessibility in mind, making it simple for visually impaired users to navigate and interact with the application.
- **Offline Support**: TensorFlow Lite models are integrated into the application, enabling offline usage without the need for a constant internet connection.

## Installation

To run Rupee Reader locally, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/your-username/Rupee-Reader.git`
2. Open the project in Android Studio or your preferred development environment.
3. Build and run the project on your Android device or emulator.

## Usage

- Upon launching the application, users can point their device's camera at an Indian currency note.
- Rupee Reader will analyze the image captured by the camera and provide feedback on the detected currency note, including its denomination.
- Users can receive this information in both voice and text formats, depending on their preferences.
- The application's user interface allows users to navigate between different features and settings easily.

## Technologies Used

- Android Studio: The primary IDE used for Android app development.
- TensorFlow Lite: TensorFlow Lite models are utilized for currency detection and recognition.
- Text-to-Speech (TTS) Libraries: Libraries such as Android's built-in TextToSpeech API are used for converting text responses into speech.
- Camera APIs: Android CameraX or Camera2 APIs are used for capturing images of currency notes.
- Gradle: Dependency management and build automation for the Android project.

## Contributing

Contributions to the Rupee Reader project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- TensorFlow: Provides resources and tools for machine learning and deep learning.
- Android Developer Documentation: Provides guidance and documentation for Android app development.
- Indian Government: For providing accessible currency notes for the visually impaired.

## Contact

For any inquiries or feedback, please contact [Ashish Phaltankar](phaltankarashish7@example.com).
