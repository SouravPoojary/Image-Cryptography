Image Encryption and Decryption Tool
This Python script allows users to encrypt and decrypt images using a password-based encryption method. It employs rail fence encryption to secure the images.

Features
Image Encryption: Encrypt your images using a password.
Image Decryption: Decrypt previously encrypted images using the correct password.
Security: Implements password-based encryption to secure images.
Prerequisites
Python 3.x installed on your system.
Required Python libraries: numpy and pillow. You can install them via pip:
Copy code
pip install numpy pillow
Usage
Clone the repository to your local machine.
Navigate to the directory where the script is located.
Run the script using Python:
Copy code
python image_crypt.py
Follow the on-screen instructions to encrypt or decrypt images.
Instructions
Encryption: Provide the image filename and a password of at least 8 characters to encrypt the image.
Decryption: Provide the encrypted image filename and the correct password to decrypt the image.
Exiting: Enter 'X' or 'x' when prompted to exit the program.
Notes
Ensure that the image files you want to encrypt or decrypt are in PNG or JPG format.
Encrypted images are saved with '-e.png' suffix appended to the original filename.
Example
Here's an example of how to use the script:

Encrypt an image:

mathematica
Copy code
Enter image filename or quit[Q/q]: example.png
Enter password: ********
Do you want to encrypt or decrypt the image or exit [E/D/X]? E
Decrypt the encrypted image:

mathematica
Copy code
Enter image filename or quit[Q/q]: example-e.png
Enter the correct password for decryption: ********
Do you want to encrypt or decrypt the image or exit [E/D/X]? D
Contributing
Contributions are welcome! Feel free to submit pull requests or open issues if you encounter any problems or have suggestions for improvement.

License
This project is licensed under the MIT License. See the LICENSE file for details.
