# Auto-Clicker

This is a simple auto-clicker script in Python using the `pynput` library that can be toggled on and off with a specific key. It allows you to automate mouse clicks by continuously clicking the left mouse button.

## Getting Started

These instructions will help you set up and run the auto-clicker on your system.

### Prerequisites

- Python 3.x
- `pynput` library: You can install it using `pip`:

    ```
    pip install pynput
    ```

### Running the Auto-Clicker

1. Clone this repository or download the `auto_clicker.py` script.

2. Open a terminal or command prompt.

3. Navigate to the directory where you saved the `auto_clicker.py` script.

4. Run the script with Python:

    ```
    python auto_clicker.py
    ```

5. The auto-clicker will start running in the background. By default, it is turned off.

6. Press the "t" key to toggle the auto-clicker on or off. While it's on, it will repeatedly click the left mouse button.

### Customization

You can customize the script by changing the toggle key or the click rate by modifying the following variables in the script:

- `TOGGLE_KEY`: Change the key code to your preferred toggle key.
- `time.sleep(0.001)`: You can adjust the delay between clicks (in seconds) to control the click rate.

## Usage Guidelines

- Be aware of the terms of service for the applications or games you are using this auto-clicker with, as it may violate their policies.

- Use the auto-clicker responsibly and avoid any activities that may cause harm or inconvenience to others.

## Contributing

Contributions are welcome. If you find a bug or have suggestions for improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This script is based on the `pynput` library for mouse and keyboard control.
- Special thanks to the open-source community for their contributions.

Happy clicking!
