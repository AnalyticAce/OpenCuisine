![Logo](logo.png)

# Open Kitchen

Open Kitchen is an AI-powered application that generates personalized recipes. It leverages the power of OpenAI to provide detailed recipes based on user input.

## Goal of the App

The goal of Open Kitchen is to revolutionize cooking by providing unique, AI-generated recipes. Users can input their favorite meals, and the app will generate a full recipe, including origin, ingredients, step-by-step instructions, and pairing suggestions.

## How to Run the App

1. Ensure you have Python installed on your machine. You can download Python [here](https://www.python.org/downloads/).

2. Clone the repository to your local machine using `git clone git@github.com:AnalyticAce/OpenCuisine.git`.

3. Install the required packages using pip:
```
pip install -r requirements.txt
```

4. Run the app using Streamlit:
```
streamlit run streamlit_app.py
```

## How to Uninstall the App

1. If you wish to uninstall the app, simply delete the cloned repository from your local machine.

2. To uninstall the Python packages that were installed for this app, you can use pip:
```
pip uninstall -r requirements.txt
```

Please note that this will only uninstall the packages listed in the `requirements.txt` file. If you have other Python packages installed that are not listed in this file, they will need to be uninstalled separately.

# Contribution Guidelines

We welcome contributions to Open Kitchen! If you'd like to contribute, please follow these guidelines:

1. **Fork the Repository**: Start by forking the OpenCuisine repository on GitHub.

2. **Clone the Forked Repository**: Clone your forked repository to your local machine using `git clone`.

3. **Create a New Branch**: Create a new branch for your contribution using `git checkout -b feature/my-contribution`.

4. **Make Changes**: Make your desired changes to the codebase. You can add new features, fix bugs, or improve existing functionality.

5. **Test Locally**: Test your changes locally by running the app using Streamlit (`streamlit run streamlit_app.py`). Ensure that everything works as expected.

6. **Commit and Push**: Commit your changes and push them to your forked repository.

7. **Create a Pull Request**: Create a pull request from your branch to the `main` branch of the original repository. Provide a clear description of your changes.

8. **Review and Merge**: The maintainers will review your pull request. Once approved, your changes will be merged into the main codebase.

## Code of Conduct

Please adhere to our Code of Conduct when contributing to this project.

Thank you for contributing to Open Kitchen!

## Disclaimer

This app uses OpenAI's GPT-3 model, which may generate unpredictable responses. Always use caution and common sense when following the generated recipes.