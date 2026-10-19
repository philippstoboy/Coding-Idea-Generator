# Coding Idea Generator

This web application is designed to help you brainstorm project ideas using the power of OpenAI's GPT-3.5-turbo. The application is built using Flask, a lightweight Python web framework, and leverages OpenAI's API to generate creative and innovative ideas for your projects.

This is an older project using the legacy `openai.ChatCompletion` interface. Compatibility with current OpenAI packages and models has not been verified.

Keep `data/api_key.txt` private and never commit your API key. Run the Flask development server locally only.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

Python 3.6 or higher

OpenAI API key

### Installation

1. Clone the repo:
```
git clone https://github.com/philippstoboy/Coding-Idea-Generator.git
```
2. Change to the project directory:
```
cd Coding-Idea-Generator
```
3. Install the required packages:
```
pip install -r requirements.txt
```
4. Set up your OpenAI API key:
```
nano data/api_key.txt
```

5. In `brainstorm.py`, replace the `data_dir` placeholder with the path to this repository's `data/` directory. Include the trailing slash because the code joins this value directly with file names:
```
nano brainstorm.py
```

## Usage

Follow these steps to use the Coding Idea Generator:

1. Run the Flask App:

 
```
python app.py
```

2. Open Browser:
 
 
The Server is now running on
```
http://localhost:5000
```
3. Generate Ideas:

 
Enter your project idea and click the "Submit" button to generate a brainstormed project plan


## Acknowledgements

- Flask: A lightweight web framework for Python
- OpenAI: The provider of the GPT-3.5-turbo API and an essential resource for the project's AI capabilities

