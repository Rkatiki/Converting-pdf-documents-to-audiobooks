# Converting-pdf-documents-to-audiobooks

This project is an implementation of a python based GUI for converting PDF documents or books into mp3 audiobooks. With the use of GUI the page number of required page or the range of pages can be provided.

**Step 1:** Converting PDF document into a stck of images using PyMuPDF 

**Step 2:** Scan the text from the images using Pytesseract OCR

**Step 3:** Google Text to Speech (gTTS) library to convert text file into audio clip

**Step 4:** Play the audio file using Pygame mixer (Can be commented out if not needed)


All the prerequisites can be downloaded by running pip install -r requirements.txt 

If any error with playing audio files using Pygame mixer copy libmpg123.dll file from pygame directory and paste it in C:/windows/system32 directory. Make sure to reboot after this problem if error persists.
