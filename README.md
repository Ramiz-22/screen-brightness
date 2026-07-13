# Screen Brightness Control

A lightweight, cross-platform desktop GUI application to view and adjust monitor brightness, built with Python.

## Features

- **View current brightness** - Shows brightness level of all connected displays
- **Set brightness** - Type a value (0-100) and press Enter or click "Set Brightness"
- **Arrow key control** - Up/Down arrows adjust brightness in 5-step increments with debounce
- **Multi-monitor support** - Handles single and multiple display scenarios
- **System theme awareness** - Automatically follows OS light/dark mode

## Usage

```bash
pip install customtkinter screen-brightness-control
python brightness_controller.pyw
```

## Interface

```
+------------------------------------------+
|  Screen Brightness Control          [-] X |
+------------------------------------------+
|          Current: 75%                      |
|  Set Brightness (0-100): [___75___]       |
|          [ Set Brightness ]                |
+------------------------------------------+
```

## Requirements

- Python 3.8+
- `customtkinter` - Modern themed GUI toolkit
- `screen-brightness-control` - Cross-platform brightness control library

## Notes

- The `.pyw` extension suppresses the console window on Windows when double-clicked
- Arrow key changes are debounced (50ms) to prevent rapid system calls during held key presses
- This project is also part of the [python-projects](https://github.com/Ramiz-22/python-projects) monorepo
