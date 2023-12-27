
# MultiLanguage Invoice Extractor

An intelligent system for understanding and analyzing invoices using Google Generative AI.

## Overview

The MultiLanguage Invoice Extractor is designed to leverage the power of Google Generative AI for analyzing invoices. Users can upload invoice images, provide input prompts, and receive detailed responses based on the content extracted from these images.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Invoice Analysis:** Analyze uploaded invoice images and provide insightful responses.
- **Input Prompt:** Users can input prompts to guide the analysis and receive targeted information.
- **Google Generative AI Integration:** Leverages Google's Generative AI for intelligent content generation.

## Getting Started

### Prerequisites

- Python > 3.9
- API Key (Set in the .env file)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/multilanguage-invoice-extractor.git
   ```

2. **Navigate to Project Directory:**

   ```bash
   cd multilanguage-invoice-extractor
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up API Key:**

   - Open the `.env` file and replace `your_api_key` with your actual API key:

     ```env
     GOOGLE_API_KEY=your_api_key
     ```

5. **Run the Streamlit App:**

   ```bash
   streamlit run app.py
   ```

6. **Access the Application:**

   - Open your web browser and go to [http://localhost:8501](http://localhost:8501).

## Usage

1. **Provide Input Prompt:**
   - Enter an input prompt describing the task or question related to the uploaded invoice image.

2. **Upload Invoice Image:**
   - Use the file uploader to upload an invoice image (in formats like png, jpg, or jpeg).

3. **Submit for Analysis:**
   - Click the "What is this?" button to trigger the analysis of the uploaded image based on the provided input prompt.

4. **View Analysis Result:**
   - The system will process the image using Google's Generative AI model and display the result.

## Configuration

Additional configuration options or customization details.

## Contributing

Contributions are welcome! Follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Streamlit
- Google Generative AI
- Other libraries/tools/resources used in the project.
```

This version now includes the major steps in your project in the "Usage" section of the README.md.