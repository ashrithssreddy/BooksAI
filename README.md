# Books AI - Book Recommendation App

BooksAI is an offline, AI-powered book recommendation application designed to provide personalized book recommendations based on user preferences. Using a fine-tuned language model, this application delivers suggestions for genres, themes, and authors that align with individual reading tastes.

## Features
- **Personalized Book Recommendations**: Generate book suggestions based on user-provided preferences.
- **Offline Model Inference**: Operate locally without requiring internet access, ensuring data privacy and security.
- **Customizable Model**: Easily adapt and fine-tune the recommendation model for specific genres or user feedback.

## Table of Contents
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started
These instructions will help you set up a local instance of BooksAI for development and testing purposes.

### Prerequisites
- Python 3.8+
- GPU (optional but recommended for faster model inference)

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ashrithssreddy/BooksAI.git
   cd BooksAI
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # For MacOS/Linux
   venv\Scripts\activate      # For Windows
   ```

3. **Install Dependencies**:
   Install the required Python packages listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Model**:
   - Use the [Hugging Face Transformers library](https://huggingface.co/transformers/) to download the GPT-2 model or another suitable model. More details are available in `docs/model_setup.md`.

### Usage
1. **Run the App**:
   After completing the setup, start the application with:
   ```bash
   python app.py
   ```

2. **Provide Book Preferences**:
   Enter genres, themes, or favorite authors to receive personalized book recommendations.

3. **Customizing Recommendations**:
   To fine-tune the model for improved recommendations, refer to `docs/fine_tuning.md`.

## Project Structure
```plaintext
BooksAI/
├── data/                    # Datasets for model fine-tuning
├── models/                  # Directory for storing downloaded model files
├── scripts/                 # Utility scripts for data processing
├── app.py                   # Main application code
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
└── docs/                    # Additional documentation
```

## Contributing
Contributions are welcome! For major changes, please open an issue to discuss what you would like to change. Make sure to follow the project's [code of conduct](CODE_OF_CONDUCT.md).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
