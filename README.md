# AI Chatbot Powered by Google Gemini for Virtual Idols

## Introduction

Vixevia is an innovative AI-based virtual YouTuber (Vtuber) that leverages the cutting-edge capabilities of Google's Gemini language model. This project aims to create a captivating and lifelike virtual personality that can engage with users through natural conversations, visual interactions, and multimedia experiences.

![Project Image Overview](https://github.com/zima-0201/Project-Images/blob/main/Gemini-Vtuber-ChatBot.png)

### Core Features

- **Natural Language Processing**: Vixevia utilizes Google's Gemini language model to understand and respond to user inputs with human-like fluency and contextual awareness.
- **Computer Vision**: The project integrates computer vision capabilities, allowing Vixevia to perceive and interpret visual information from the environment.
- **Multimodal Interaction**: Vixevia combines speech recognition, text-to-speech synthesis, and visual processing to facilitate seamless multimodal interactions with users.
- **Personalized Responses**: Vixevia's responses are tailored to the conversational context, user preferences, and situational dynamics, ensuring engaging and personalized experiences.
- **Virtual Avatar**: Vixevia is represented by a visually appealing and expressive virtual avatar, bringing her personality to life.

## System Architecture

This project is built on a microservices architecture, integrating various external services and APIs to provide a seamless user experience:

- **Google Cloud Platform**: Integrates multiple API services to leverage the capabilities of the Gemini language model and computer vision.
- **PostgreSQL Database**: Manages user data, including conversation histories and preferences, ensuring secure and efficient access to user-specific settings.
- **Python Environment**: The entire backend logic is implemented in Python, taking advantage of its rich ecosystem of libraries for HTTP requests, database connections, and environmental variables management.

## Prerequisites

- 5+ API keys from Google Cloud Platform
- Python 3.12+

Hardware:
- 16 GB VRAM
- 32 GB RAM
- RTX 4050 or better
- 20 GB of storage
- i7 12th gen or better, or AMD equivalent

## Installation and Setup

To get started with Vixevia, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/IRedDragonICY/vixevia.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Obtain the necessary API keys and configuration files from Google Cloud Platform.
4. Update the configuration files with your API keys and preferred settings.
5. Run the main script:

   ```bash
   python main.py
   ```

## Usage and Commands

After setup, users interact with Vixevia through a series of commands and interactive buttons, enabling them to set up their environment, initiate conversations, and receive personalized responses. The bot's intuitive design ensures a smooth and engaging user experience.

## Future Enhancements

The project roadmap includes features such as:

- Creating a custom Live2D model for Vixevia.
- Adding OpenCV auto labeling to recognize and remember individuals using Gemini Pro Vision.

## Contributing to the Project

We welcome contributions from the community to make Vixevia more robust, feature-rich, and accessible. Refer to the Contributing section above for guidelines on making contributions.

## Support and Feedback

Your feedback and questions are valuable to us. For support, feature requests, or to report bugs, please open an issue in the project repository or contact the project maintainers directly.

## License

This project is licensed under the [MIT License](LICENSE), which allows for redistribution, use, and modification under specified terms.

## Acknowledgments

- Google's Gemini language model and related technologies
- Open-source libraries and frameworks used in this project

Vixevia is an experimental project aimed at exploring the possibilities of AI-based virtual personalities and pushing the boundaries of human-computer interaction. We hope this project inspires further innovation and collaboration in the field of artificial intelligence and virtual content creation.
