# Login Menu with Enhanced Security

This is a simple login menu with enhanced security features to prevent XSS attacks and element inspection. It includes HTML, CSS, and JavaScript files.

## Features

- Secure input sanitization to prevent XSS (Cross-Site Scripting) attacks.
- Protection against element inspection through the developer tools.

## Technologies Used

- HTML
- CSS
- JavaScript

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/login-menu.git
   ```

2. Navigate to the project directory:

   ```bash
   cd login-menu
   ```

3. Open the `login.html` file in a web browser to see the login menu.

## Security Measures

### Input Sanitization

The JavaScript code includes a `sanitizeInput()` function that sanitizes user input to prevent XSS attacks. It removes characters that are commonly used in XSS attacks such as `<`, `>`, `"`, `'`, and ```.

### Element Inspection Prevention

The JavaScript code also includes a `preventInspectElement()` function that prevents element inspection through the developer tools. It replaces the `console.log` function with an empty function and alerts the user when the inspect element feature is opened.

Please note that these security measures are not exhaustive, and additional security practices should be implemented depending on the framework and technologies used.

## License

This project is licensed under the [MIT License](LICENSE).
```

Note: Pastikan untuk menyertakan file `LICENSE` jika Anda ingin menggunakan lisensi MIT atau gantilah dengan lisensi yang sesuai.
