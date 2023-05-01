# AppName

[description]

Endpoint: 

## Getting Started

To begin using the StoryCraft application, follow the steps outlined below:

1. Clone the repository to your local machine.
2. Install [Poetry](https://python-poetry.org/docs/#installation) on your local machine if not already present.
3. Navigate to the root directory of the project and execute `poetry install` to install the required dependencies.
4. Set your OpenAI API key as a streamlit secret with the name `OPENAI_API_KEY`.
5. Run `poetry run streamlit run ./app/main.py` to initiate the application.
6. Access the application by opening the URL displayed in the console.

## Usage

[Usage]

## Dependencies

[AppName] employs [Poetry](https://python-poetry.org/) for dependency management. 
The following packages are necessary to run the application:

- python = "3.9.16"
- streamlit = "^1.22.0"
- openai = "^0.27.5"

Access to OpenAI's language model requires an API key.

## Credits and Licensing

Developed by Shashank Kapadia, StoryCraft is released under the [MIT License](https://opensource.org/licenses/MIT). 
The application utilizes OpenAI's language model, subject to OpenAI's terms of service.

## Code Attribution

If you plan to use any portion of the [AppName] source code in your own projects, please provide proper 
attribution by including the following in your documentation or source code:
````json
{
  "Project": "[AppName]",
  "Developer": "Shashank Kapadia",
  "Source": "https://github.com/kapadias/story-craft",
  "License": "MIT License"
}
````
