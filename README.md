# Sombrero

A modern, colorful Markdown renderer for the terminal with advanced styling and formatting capabilities.

## Features

- **Rich Text Formatting**: Bold, italic, code, and links with distinct styling
- **Advanced Element Support**: Tables, code blocks with syntax highlighting, blockquotes, and horizontal rules
- **Image Support**: Terminal image rendering (when `term-image` is available)
- **Custom Styling**: Automatic color theming with random accent colors for headings
- **Unicode Support**: Special bullets and symbols for enhanced visual appearance
- **Programming Language Icons**: Visual indicators for code blocks

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/sombrero.git
cd sombrero

# Install dependencies
pip install pygments
pip install term-image  # Optional, for image rendering support

# Add to your PATH (optional)
ln -s $(pwd)/sombrero.py /usr/local/bin/sombrero
chmod +x /usr/local/bin/sombrero
```

## Usage

```bash
# Render a markdown file
python sombrero.py example.md


```

## Requirements

- Python 3.6+
- Pygments (for syntax highlighting)
- term-image (optional, for image rendering)
