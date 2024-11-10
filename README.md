# Oak Tree Art Generator

Welcome to the **Oak Tree Art Generator**, an AI-powered web application designed for the **Oak Hall School AI Prompt Engineering Enrichment Program**. This tool enables students from grades 4 to 8 to create unique, AI-generated artwork of oak trees by selecting various artistic elements through a guided interface.

**Live Demo:** [https://sounny.github.io/oakartai/](https://sounny.github.io/oakartai/)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Guided Prompt Creation**: Students can select from various options such as oak tree type, lighting, composition, art style, medium, and more.
- **Additional Elements**: A freeform text area allows students to add unique details to their artwork.
- **AI-Generated Art**: Utilizes the Pollinations.AI API to generate high-resolution images based on the constructed prompts.
- **Display Full Prompt**: Shows the full prompt used to generate the image, enhancing educational value.
- **Download Options**:
  - **Download Image**: Save the generated image directly.
  - **Download Gallery PDF**: Generates a PDF formatted for printing, including the image, student's name, grade, caption, and a QR code linking to the image.
- **QR Code Generation**: Provides a QR code that links directly to the generated image on Pollinations.AI.
- **Seed Number**: Option to input a seed number for consistent outputs.

## Technologies Used

- **HTML5 & CSS3**: For structuring and styling the web application.
- **JavaScript**: For client-side scripting and interactions.
- **[Pollinations.AI API](https://pollinations.ai/)**: For AI image generation.
- **[jsPDF](https://github.com/parallax/jsPDF)**: To generate PDF files on the client side.
- **[html2canvas](https://html2canvas.hertzen.com/)**: To capture images for PDF generation.
- **[Google Fonts](https://fonts.google.com/)**: For custom fonts.
- **[QR Server API](https://goqr.me/api/)**: To generate QR codes.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (required for API calls and CDN resources)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/oakartai.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd oakartai
   ```

3. **Open the `index.html` file** in your preferred web browser:

   - You can double-click the `index.html` file, or
   - Use a local web server for better results.

## Usage

1. **Open the Application**:

   - Visit the live demo: [https://sounny.github.io/oakartai/](https://sounny.github.io/oakartai/)
   - Or open `index.html` locally.

2. **Fill Out the Form**:

   - **Student Name**: Enter your name.
   - **Grade**: Enter your grade (4-8).
   - **Select Options**: Choose from various options for oak tree type, lighting, composition, art style, medium, and more.
   - **Additional Elements**: Optionally add your own creative details.
   - **Seed Number**: (Optional) Enter a seed number for consistent outputs.

3. **Generate Art**:

   - Click on the **"Generate Art"** button.
   - Wait for the image to be generated (this may take a few moments).

4. **View and Download**:

   - The generated image and full prompt will be displayed.
   - Use the **"Download Image"** button to save the image.
   - Use the **"Download Gallery PDF"** button to save a printable PDF.

5. **QR Code**:

   - Scan the QR code to view the image on Pollinations.AI.

## Project Structure

```
oakartai/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css  # If styles are external
    └── js/
        └── script.js   # If scripts are external
```

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix:

   ```bash
   git checkout -b feature-name
   ```

3. **Make your changes** and commit them:

   ```bash
   git commit -m 'Add new feature'
   ```

4. **Push to the branch**:

   ```bash
   git push origin feature-name
   ```

5. **Create a Pull Request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Oak Hall School**: For inspiring this educational project.
- **Pollinations.AI**: For providing the AI image generation API.
- **jsPDF** and **html2canvas**: For enabling PDF generation on the client side.
- **QR Server API**: For QR code generation.
- **All contributors and students** who have participated in making this project successful.

---

If you have any questions or need further assistance, feel free to open an issue or contact the project maintainer.

---

**Note**: Replace `yourusername` in the git clone URL with your actual GitHub username if you plan to clone the repository.
