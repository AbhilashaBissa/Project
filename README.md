SteganoCrypt - Image Steganography Tool

SteganoCrypt lets you securely hide secret messages within images using Least Significant Bit (LSB) encoding. It ensures safe message embedding and retrieval through passcode protection.

🚀 Features

Encrypt Messages: Hide text inside an image using LSB.

Decrypt Messages: Extract hidden messages securely with a passcode.
Passcode Protection: Only authorized users can access the hidden messages.
Simple & Fast: Built with OpenCV and standard Python libraries.
No External Dependencies: Works without requiring NumPy.
📦 Installation
Ensure Python 3 and Git are installed on your system.

Install OpenCV using pip:

pip install opencv-python

Clone the repository:

git clone https://github.com/Nishant9592/SteganoCrypt.git

⚡ Usage
Encrypt a Message into an Image
Run the following command:

python3 encryption.py

Enter the image path (supports .png, .jpg, .jpeg).
Specify the output file name (must be .png).
Provide the secret message to hide.
Set a passcode for protection.
The encrypted image will be saved!
Decrypt a Hidden Message
Run the following command:

python3 decryption.py

Enter the path of the encrypted image.
Provide the correct passcode.
The secret message will be revealed!
🔧 Requirements
Python 3.x
OpenCV (opencv-python)

⚠️ Notes & Warnings
If using Linux or macOS, run with python3 encryption.py/decryption.py.
Save the output image in PNG format to preserve hidden data.
If the passcode is incorrect, the message cannot be retrieved.
Large messages may not fit in smaller images; use high-resolution images for larger messages.

📜 License
This project is open-source and free to use!

