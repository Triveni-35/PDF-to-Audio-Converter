# PDF-to-Audio-Converter
This Python project converts text from PDF files into spoken audio using the Google Text-to-Speech (gTTS) library. It utilizes PyPDF2 to extract text from the PDF and generates an MP3 audio file of the extracted content.



<br>
Features:
Extracts text from PDF files.
Converts extracted text to speech in MP3 format.
Supports multiple languages through gTTS.
Restrictions:
File Size: Large PDFs may cause performance issues due to memory consumption and processing time.
Content Limitations:
Scanned PDFs may require OCR for text extraction.
Encrypted PDFs need to be decrypted for access.
Custom fonts and special formatting may affect text readability.
Usage:
Ensure Python and required libraries (gtts, PyPDF2) are installed.
Place the target PDF file in the same directory as the script.
Run the script to generate an audio file.
