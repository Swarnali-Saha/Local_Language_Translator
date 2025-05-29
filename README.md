# 🌐 Local Language Translator

A lightweight and intuitive web application that allows users to translate text between multiple languages. Users can either type text directly or upload documents for translation. The app also supports automatic detection of the input language and provides the option to download the translated output.

#
🚀 __Project Objective__

To build a simple, responsive, and user-friendly website that enables seamless translation between various languages, using basic frontend technologies (HTML, CSS, and JavaScript) and integrates with the Google Translate API.

#
📌 __Project Scope__

This project focuses on the following:

- Multi-language support with an interactive dropdown menu

- Auto-detection of the input language (if not manually selected)

- Translation via text input or file upload (PDF, DOC, DOCX, TXT)

- Real-time character count tracking

- Option to download translated text

- Swap functionality for input/output languages

#
🛠️ __Technologies Used__

- __HTML5:__ for structuring the webpage

- __CSS3:__ for styling and layout

- __JavaScript:__ for interactivity and translation logic

- __Google Translate API__ (unofficial via translate.googleapis.com)

- __FileReader API:__ to read uploaded files

#
🔁 __Steps Followed__

- Built a responsive UI using HTML and CSS.

- Implemented dropdown menus for language selection.

- Integrated Google Translate API for translation functionality.

- Added file upload support using the FileReader API.

- Developed auto-language detection by leaving the source language unselected.

- Enabled download functionality of translated text using Blob and anchor elements.

- Integrated swap functionality to interchange input and output languages.

- Included input character count feedback for user awareness.

#
❓ __Key Questions Addressed__

- How can we translate text between languages with minimal backend setup?

- Can we enable translation for both typed and uploaded content?

- How do we manage user input limitations (e.g., 5000 character cap)?

- What is the best way to handle unsupported file types and ensure user-friendly alerts?

- How can we allow users to download the translated text seamlessly?

#
📈 __Summary of Key Insights__

- The Google Translate endpoint used (translate.googleapis.com) works effectively without an API key for basic use cases.

- File reading and translation must be handled asynchronously to provide smooth user experience.

- Providing visual feedback like character count, file name display, and toggle themes improves usability.

- Handling edge cases such as large files, unsupported formats, and null inputs ensures a robust application.

#
📷 __Features in Action__

- Input text via textarea or document upload

- Auto language detection

- Translation via Google Translate

- Swap source and target languages

- Download translated text

- Responsive UI with dark mode

- Input character limit with live counter

#
📂 __File Upload Support__

- __Supported formats:__

  - .txt

  - .pdf (as text only)

  - .doc / .docx

  - Unsupported files will trigger a friendly alert.

#
📥 __Download Feature__

- Translated output can be downloaded in .txt format.

- File name includes target language code (e.g., translated-to-es.txt).

#
📷 __Screenshot__

Below is a screenshot of the Local Language Translator website:

![Screenshot of the website](https://github.com/Swarnali-Saha/Local_Language_Translator/blob/main/translator.png)
