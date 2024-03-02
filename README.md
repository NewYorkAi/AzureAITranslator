# AzureAI Translator Web App

A Flask web application leveraging Azure Cognitive Services for text translation. Set up your .env, and you're ready to translate!

AzureAI Translator is a web application built with Flask, leveraging the powerful Azure Cognitive Services to provide seamless text translation. Designed with simplicity and efficiency in mind, this application serves as an exemplary model for integrating Azure's robust translation services into your own projects.

## Features

- Text translation with support for multiple languages.
- Easy-to-use, minimalist web interface.
- Environment variable configuration for secure credential management.
- Extensible codebase for further customization and scalability.

## Getting Started

Follow these instructions to set up the application on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or later.
- Flask
- An active Azure subscription with access to Cognitive Services.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/NewYorkAi/AzureAITranslator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd AzureAITranslator
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up your `.env` file with your Azure credentials. Duplicate the `.env.sample` file, rename it to `.env`, and fill in the values:

    ```plaintext
    KEY=your_azure_key_here
    ENDPOINT=your_azure_endpoint_here
    LOCATION=your_azure_location_here
    ```

## Running the Application

Start the application with:

```bash

flask run
````
Access it at http://localhost:5000

### Contributing

Contributions to enhance AzureAI Translator are warmly welcomed. Whether it's bug fixes, new features, or improvements to the documentation, we value your input.

1. Fork the repository.
2. Create a new branch ```git checkout -b feature/AmazingFeature ```
3. Commit your changes ``` git commit -m 'Add some AmazingFeature' ```
4. Push to the branch ``` git push origin feature/AmazingFeature ```
5. Open a pull request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments

Azure Cognitive Services
Flask Community
Contributors who share their invaluable insights.

### Contact

### Project Link: https://github.com/NewYorkAi/AzureAITranslator

For support or collaboration inquiries, please reach out through GitHub issues or contact me directly.
