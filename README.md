**Title**

*Simple Image Pixel Manipulation*

**Description**

This Python program demonstrates basic image manipulation techniques using the Pillow library. It allows you to perform a simple encryption and decryption process on images by swapping red and blue pixel channels.

**How to Use**

1. **Prerequisites:**
   - Install the Pillow library: `pip install Pillow`

2. **Save the code:**
   - Save the provided code as a Python file (e.g., `pixel_manipulation.py`).

3. **Run the script:**
   - Open your terminal and navigate to the directory where you saved the script.
   - Execute the script using the following command:

     ```bash
     python pixel_manipulation.py
     ```

   **Note:** This script uses hardcoded file paths for demonstration purposes. You'll need to modify these paths to point to your desired input and output images. Here's an example with placeholders:

     ```bash
     python pixel_manipulation.py "path/to/your/input_image.jpg" "path/to/encrypted_image.jpg" "path/to/decrypted_image.jpg"
     ```

**Understanding the Code**

- The script utilizes the Pillow library to load, manipulate, and save images.
- The `encrypt_image` function opens the input image, iterates through each pixel, swaps the red and blue channel values, and saves the modified image as the encrypted version.
- The `decrypt_image` function performs the reverse operation, swapping the channels back to their original positions, effectively decrypting the image.

**Disclaimer**

This code is intended for educational purposes only. It highlights a basic pixel manipulation technique but does not provide robust security for image encryption.

**License**

This project is licensed under the MIT License.

**Feel free to use this code for learning and experimentation!**
