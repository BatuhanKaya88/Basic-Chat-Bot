# Basic-Chat-Bot
This is a simple exercise project that I did to improve myself in artificial intelligence and understand how Natural Language Understanding (NLU) elements work. In this project, I used the natural language understanding method using the rasa library in Python and practiced by making a basic chat bot. The project is open to development and has errors.
## Installation
1. Create a new Python project.
2. Install RASA by running the following command in the terminal:
```
pip install rasa
```
3. Clone or download this repository and copy the provided folder into your Python project directory.

## Usage
To train and interact with the Turkcell Assistant, follow these steps:
1. Open a terminal and navigate to your Python project directory.
2. Train the NLU (Natural Language Understanding) model:
```
rasa train nlu
```
3. Train the core model:
```
rasa train
```
4. Start the shell to chat with the Turkcell Assistant:
```
rasa shell
```
## Note
Because of the way the code is written, training the model can take a while and the model file size can be huge. Please be patient in this process.

Adjusting the `epochs` parameters in the `config.yml` file can significantly impact training time. By reducing the value of `epochs`, you can decrease the number of training iterations, thus reducing the overall time required for training.


## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License
This project is licensed under the [MIT License](LICENSE.txt).
Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your changes to your fork.
Submit a pull request to the main repository.
