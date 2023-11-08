# Building a chatbot using Rasa

Building Chatbot using Rasa is a project aimed at leveraging machine learning and AI to assist users in accomplishing tasks more efficiently.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Training a Model](#training-a-model)
- [Running the Chatbot](#running-the-chatbot)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

```
git clone https://github.com/UitsTanVirH/rasa_chatbot.git
cd rasa_chatbot
```
   
Create a Virtual Environment:
```
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```
Install Dependencies:

```
pip install rasa
```

## Usage
Building Chatbot using Rasa is designed to help users perform tasks faster through the power of machine learning and AI. To use the chatbot, follow these steps:

Customize the chatbot to your needs (see Customization).
Train the Rasa model (see Training a Model).
Run the chatbot (see Running the Chatbot).

## Customization
Customize the chatbot to suit your specific use case by modifying the domain file, adding custom actions, and adjusting configurations. Review the domain.yml file and the actions directory for customization options.

## Training a Model
Train the Rasa model to enhance the chatbot's performance. Use the following command to train the model:

```
rasa train
```
## Running the Chatbot
Run the Rasa server and the action server to start the chatbot. Use the following commands:

```
rasa shell
rasa run actions
```
## Contributing
If you wish to contribute to this project, please follow the guidelines in CONTRIBUTING.md.

## License
This project is licensed under the [Your License] - see the LICENSE file for details.

