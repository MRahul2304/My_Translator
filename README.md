# My Translator

## Overview

My Translator is a simple desktop application that allows users to translate text between different languages. Built using Python's Tkinter library for the graphical user interface and Deep Translator for the translation functionality, this app supports a variety of languages.

## Features

- **Translate Text**: Input text in one language and translate it to another.
- **Language Selection**: Choose source and destination languages from a dropdown menu.
- **Text Input & Output**: Enter text in a source text box and view translated text in a destination text box.

## Technologies Used

- **Python**: Programming language used for the application.
- **Tkinter**: Library used for creating the graphical user interface.
- **Deep Translator**: API used for text translation.
- **Google Translator**: Service utilized for translation through Deep Translator.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/my-translator.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd my-translator
    ```

3. **Install dependencies**:

    Ensure you have `pip` installed, then run:

    ```bash
    pip install deep-translator
    ```

4. **Run the application**:

    ```bash
    python my_translator.py
    ```

## Usage

1. **Enter the text** you want to translate in the "Source Text" box.
2. **Select the source language** from the "Source Language" dropdown.
3. **Select the destination language** from the "Destination Language" dropdown.
4. **Click "Translate"** to get the translated text displayed in the "Destination Text" box.

## Code Explanation

- `get_language_code(language_name)`: Retrieves the language code for a given language name.
- `change(text, src, dest)`: Translates text from the source language to the destination language.
- `data()`: Handles the translation process based on user input.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions to improve the app or add features are welcome.
