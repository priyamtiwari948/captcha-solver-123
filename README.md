# CAPTCHA Solver Demo

This project provides a simple, single-file web application demonstrating a client-side CAPTCHA input and validation system. It uses Tailwind CSS for a modern, responsive user interface.

## Features

*   **Responsive Design**: Built with Tailwind CSS, ensuring a consistent experience across various devices.
*   **Dynamic Image Loading**: The CAPTCHA image can be loaded from a URL specified in the query parameters.
*   **Client-Side Validation**: A basic validation mechanism for demonstration purposes.

## Getting Started

To run this application, simply open the `index.html` file in your web browser. No special server setup or build process is required.

### Prerequisites

*   A modern web browser.

### Usage

1.  **Default CAPTCHA**:
    Open `index.html` directly in your browser. The application will display the `sample.png` image as the CAPTCHA. The expected solution for this image is "ADURS".

2.  **Custom CAPTCHA Image (for demonstration)**:
    You can specify an external image URL using the `url` query parameter. For example:
    `index.html?url=https://example.com/some-captcha-image.png`
    
    *Note*: For external images, the client-side validation will still be performed against the hardcoded "ADURS" solution, as this is a front-end only demo and does not integrate with a real CAPTCHA solving backend. This feature is primarily for demonstrating dynamic image loading.

## Project Structure

*   `index.html`: The main single-file HTML application.
*   `README.md`: This README file.
*   `LICENSE`: The MIT License for the project.
*   `sample.png`: The default CAPTCHA image used when no URL parameter is provided.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.