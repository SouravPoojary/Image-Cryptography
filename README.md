# ImageCrypt

ImageCrypt is a Python script designed to encrypt and decrypt image files using a password-based encryption method. The script leverages the PIL library for image processing and the numpy library for array manipulations.

## Installation

Ensure you have the required libraries installed by executing the following command:

```bash
pip install numpy pillow
```

## Usage

To run the script, execute:

```bash
python image_crypt.py
```

Follow the prompts to provide the image filename and password.

- Choose the mode: encrypt (E) or decrypt (D).
- The script will process the image and save the output as a new image file (encrypted or decrypted).
- Repeat the process to continue encrypting or decrypting images.
- To exit, enter 'x' or 'X' when prompted for the mode.

## How it Works

The script follows this encryption and decryption process:

1. **Reading the Image**: The script reads the image file and converts it into a list of RGB pixel values.

2. **Password Processing**: The password is converted into a list of ASCII codes.

3. **Rail Fence Cipher**: The pixel list is encrypted using the Rail Fence Cipher technique with the password.

4. **Reconstructing the Image**: The encrypted or decrypted pixel list is rearranged to recreate the image.

5. **Saving the Output**: The resulting image is saved as a new file with the '-e' or '-d' suffix.

## Note

While the script employs a password-based encryption method, it is not suitable for serious security purposes due to its lack of cryptographic robustness. It is recommended for educational and entertainment purposes only.
