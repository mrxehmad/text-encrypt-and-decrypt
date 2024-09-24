This project is a web-based application that allows users to encrypt and decrypt messages using AES encryption. The user can input a message and a key (password), and the application will encrypt or decrypt the message accordingly. The interface is built using Bootstrap for responsive design and utilizes JavaScript (with the CryptoJS library) for encryption and decryption functionality.

---

## **Features**

- **Message Encryption**: Users can enter plain text and a key to encrypt the message. The result is an encrypted text that can be securely shared.
- **Message Decryption**: Users can input encrypted text along with the key to decrypt it back into its original form.
- **Copy Functionality**: Easily copy the encrypted or decrypted message to the clipboard.
- **Full-Screen Layout**: A simple and clean interface with full-screen containers for both encryption and decryption.
- **Responsive Design**: The application is built using Bootstrap to ensure a mobile-friendly and responsive user experience.

---

## **Technologies Used**

- **HTML5**: Markup structure for the web page.
- **CSS3 (Bootstrap)**: For styling and responsive design.
- **JavaScript**: For client-side interactivity and functionality.
- **CryptoJS**: A JavaScript library used for AES encryption and decryption.
- **Local and External CDN**: Local CDN links are used for faster loading, with fallbacks to external CDNs.

---

## **Setup & Installation**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/message-encode-decode.git
   cd message-encode-decode
   ```

2. **Open the Application**:
   Simply open the `index.html` file in your browser to run the application.

---

## **Usage Instructions**

1. **Encrypt a Message**:
   - Click the **Encrypt** button at the top-right of the menu bar.
   - Enter the text you want to encrypt and a key (password).
   - Press **Convert** to see the encrypted text.
   - Click **Copy** to copy the encrypted text to your clipboard.

2. **Decrypt a Message**:
   - Click the **Decrypt** button at the top-right of the menu bar.
   - Enter the encrypted text and the same key used for encryption.
   - Press **Convert** to reveal the decrypted message.
   - Click **Copy** to copy the decrypted text to your clipboard.

---

## **Fallback Mechanism for External Resources**

The application uses local CDN URLs for Bootstrap, jQuery, Popper.js, and CryptoJS. In case the local CDN is unavailable, it automatically falls back to the corresponding external CDN.

Example of fallback for Bootstrap:
```html
<link href="http://file.local/Guest/cdn/bootstrap.min.css" rel="stylesheet" 
      onerror="this.onerror=null;this.href='https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css';">
```

---

## **Obfuscation**

For enhanced security, the JavaScript code handling encryption and decryption can be obfuscated using a tool like [JavaScript Obfuscator](https://javascriptobfuscator.com/). This adds a layer of protection, making the code harder to read and modify.

---

## **Limitations**

- **Client-Side Encryption**: This application handles encryption and decryption on the client side using JavaScript, which means it is less secure compared to server-side encryption. Use it for non-sensitive data or local experimentation.
- **Key Sensitivity**: Ensure the correct key is used for both encryption and decryption, as mismatched keys will result in errors or incorrect decryption.

---

## **Contributing**

If you want to contribute to this project, feel free to submit a pull request. Please ensure your code is well-documented and follows best practices.

---

## **License**

This project is open-source and licensed under the MIT License.

---

## **Contact**

For any questions or support, contact [AHMADFARAZWARRICH@GMAIL.COM].

---

## **Screenshots**

### 1. Encryption Page
![Encryption page screenshot](screenshots/encryption-page.png)

### 2. Decryption Page
![Decryption page screenshot](screenshots/decryption-page.png)
