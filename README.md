# Kanye Says... Quote Generator

A simple Tkinter-based GUI application that fetches and displays random Kanye West quotes from an API.

## Features
- Displays random Kanye West quotes
- Updates quote with button click
- Clean GUI with background image
- Initial quote loaded on startup

## Prerequisites
- Python 3.x
- Required Python packages:
  - `tkinter` (usually included with Python)
  - `requests`
- Required assets:
  - `background.png` (300x414 pixels)
  - `kanye.png` (button image)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/kanye-quote-generator.git
cd kanye-quote-generator
```

2. Install dependencies:
```bash
pip install requests
```

3. Ensure image files are in the project directory

## Usage
1. Run the application:
```bash
python kanye_quote.py
```

2. Use the GUI:
- Click the Kanye button to fetch a new quote
- Initial quote loads automatically

## How It Works
- Fetches quotes from `https://api.kanye.rest`
- Displays quote on a canvas with background
- Updates text via button command
- Centers quote with word wrapping

## File Structure
- `kanye_quote.py`: Main application file
- `background.png`: Background image (required)
- `kanye.png`: Button image (required)

## GUI Components
- Canvas (300x414) with background image
- Quote text (white, Arial 30 bold)
- Kanye button to fetch new quotes

## API Used
- Kanye REST API: `https://api.kanye.rest`

## Customization
- Window padding: `padx=50, pady=50`
- Canvas size: 300x414
- Text width: 250 pixels
- Font: Arial, 30, bold
- Image file names/paths

## Notes
- Raises exception on API failure
- Quote text wraps at 250 pixels
- Images must be in same directory
- Initial quote displayed on launch

## Requirements.txt
```
requests
```

## Limitations
- Single API source
- No offline mode
- Basic error handling (raises exception)
- Fixed window size

## License
[MIT License](LICENSE)

## Disclaimer
- Ensure image files are present
- Requires internet connection
- API availability dependent
- No quote history or saving
```
