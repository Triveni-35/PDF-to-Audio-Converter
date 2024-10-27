# PDF-to-Audio-Converter
This Python project converts text from PDF files into spoken audio using the Google Text-to-Speech (gTTS) library. It utilizes PyPDF2 to extract text from the PDF and generates an MP3 audio file of the extracted content.



<br>
Features:<br>

Extracts text from PDF files.<br>

Converts extracted text to speech in MP3 format.<br>

Supports multiple languages through gTTS.<br>

Restrictions:<br>

File Size: Large PDFs may cause performance issues due to memory consumption and processing time.<br>

Content Limitations:<br>

Scanned PDFs may require OCR for text extraction.<br>

Encrypted PDFs need to be decrypted for access.<br>

Custom fonts and special formatting may affect text readability.<br>

Usage:<br>

Ensure Python and required libraries (gtts, PyPDF2) are installed.<br>

Place the target PDF file in the same directory as the script.<br>

Run the script to generate an audio file.<br>

