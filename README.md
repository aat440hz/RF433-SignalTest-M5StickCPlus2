# RF433 Signal Test for M5StickCPlus2

This project demonstrates a simple RF433 signal test for M5StickCPlus2 using the ESP32's RMT peripheral. It displays the received signal's waveform on the M5StickCPlus2 screen, allowing you to visualize the signal.

## Features

- Measures RF433 signal using the RMT peripheral.
- Displays the signal waveform on the M5StickCPlus2 screen.
- Adjustable signal strength threshold for better visualization.

## Requirements

- M5StickCPlus2 board
- RF433R receiver module
- Arduino IDE or PlatformIO

## Installation

1. Clone or download this repository.
2. Open the project in Arduino IDE or PlatformIO.
3. Connect your M5StickCPlus2 board to your computer.
4. Upload the code to your M5StickCPlus2 board.

## Usage

1. Ensure your RF433R receiver module is connected to the grove connector on the M5StickCPlus2.
2. Power on your M5StickCPlus2.
3. The signal waveform will be displayed on the screen, representing the signal.
4. Adjust the `SIGNAL_STRENGTH_THRESHOLD` constant in the code to change the signal strength threshold for better visualization.

## License

This project is licensed under the [MIT License](LICENSE).
