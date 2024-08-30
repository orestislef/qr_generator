This Flutter project is a customizable QR code generator that allows users to create, customize, and export QR codes. The app includes several features for tailoring the appearance of the QR code, such as selecting the shape of the symbols, adding images, and picking custom colors.

## Features

- **Text/URL Input**: Enter the text or URL that you want to encode into a QR code.
- **Rounded or Smooth Symbols**: Toggle between rounded or smooth symbols for your QR code.
- **Image Integration**: Optionally add an image to the center of your QR code.
- **Customizable Colors**: Choose the color for the QR code using a color picker.
- **QR Code Export**: Export the generated QR code as a PNG image.

## Getting Started

### Prerequisites

- Flutter SDK
- Dart

### Installing

1. Clone the repository:

   ```bash
   git clone https://github.com/orestislef/qr_generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd qr-code-generator
   ```

3. Get the dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

### Usage

- Enter the data you want to encode in the QR code.
- Customize the appearance of the QR code using the provided options.
- Click on "Export QR Code" to save your generated QR code as an image.

### Project Structure

- **lib/main.dart**: The main file containing the app's UI and logic.
- **assets/**: Contains any assets used by the app (images, icons, etc.).

### Dependencies

This project makes use of the following Flutter packages:

- `flutter_hsvcolor_picker`: A color picker widget for Flutter.
- `pretty_qr_code`: A package for generating visually appealing QR codes.
- `screenshot`: A package to take screenshots of widgets.

### Contributing

Contributions are welcome! Feel free to open a pull request or issue.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contact

If you have any questions or feedback, feel free to reach out at [your.email@example.com](mailto:your.email@example.com).

---

Thank you for checking out this project! If you find it useful, please consider giving it a star on GitHub. 🌟
```