📌 Overview

This project extracts text from an image using Tesseract OCR and converts it into speech using Google Text-to-Speech (gTTS). It processes the image, enhances text clarity, and generates an audio file with the extracted content. This can be particularly helpful for visually impaired individuals, enabling them to access textual information through audio output.

🛠 Features

- Image Preprocessing - Converts to grayscale, removes noise, and applies thresholding.
- OCR with Tesseract - Extracts text from images efficiently.
- Text-to-Speech - Converts recognized text into an MP3 audio file.
- Automated Playback - Plays the generated speech file after processing.
- Accessibility Support - Assists visually impaired users by providing audio representation of text.

🔧 Installation

1.Clone the repository

2.Install dependencies:
 
```
$ pip install numpy

$ pip install PIL

$ pip install opencv-python

$ pip install pytesseract

$ pip install gTTS
```
 
3.Install Tesseract OCR:

```
 pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
```
 
4.Run Python File

🤝 Contributing

Feel free to fork this repo and submit pull requests. Let's build something amazing together! 🚀
