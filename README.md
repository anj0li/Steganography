
# Secure Data Hiding in Images using Steganography (Python)
This project demonstrates a simple implementation of image steganography using Python and OpenCV. The application allows users to hide (encrypt) a secret message inside an image and later retrieve (decrypt) the message using a simple UI built with Tkinter.

## Features
- Data Hiding (Encryption):
Embed a secret text message into a cover image. The program writes each character's ASCII value into the image pixels (using a diagonal embedding method) and saves the modified image as a lossless PNG file to preserve data integrity.

- Decryption:
Retrieve the hidden message from the modified image by providing the correct passcode and the message length.

- Graphical User Interface (GUI):
A simple Tkinter-based UI to facilitate the process of:

## Basic Steps of Implementaion
Uploading a cover image.
Entering the secret message and passcode.
Encrypting (hiding) the message in the image.
Uploading an encrypted image.
Decrypting (extracting) the hidden message.

## Requirements
- Python 3.x
- OpenCV 
(installation command)
```sh
pip install opencv-python
```  

## Screenshot
![2](https://github.com/user-attachments/assets/1e58db5c-4c66-471c-9096-b75ddf81726f)
![1](https://github.com/user-attachments/assets/42370722-f32f-45f6-8861-f85fcadcdfc8)

