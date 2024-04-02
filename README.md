# FareFlightAssistant



This project is an implementation inspired by the "Auto Gen Flights Tutorial" created by John Adeojo, Founder and Chief Data Scientist at Data-centric Solutions. This repository is developed to complement the insights and instructions shared in the [original blog post](URL_to_the_blog_post) and [YouTube video](URL_to_the_YouTube_video). Full credit goes to John Adeojo and Data-centric Solutions for the original idea and tutorial.

## Prerequisites

Before you begin, ensure you have access to the following:

- **Amadeus**: Sign up at the Amadeus Developer Platform to obtain your API Key and Secret Key. [Developer Sign-up](https://developers.amadeus.com/sign-up)
- **Neon**: Sign up to Neon and create a project. [Neon Sign-up](URL_to_Neon_signup)
- **OpenAI**: Obtain an OpenAI API key. [OpenAI API Access](https://openai.com/api/)

**Note**: It's essential to name your database `flights_data` to match the codebase without requiring additional modifications.

## Getting Started

To utilize this repository effectively, follow these steps:

1. Clone this repository to a local directory.
2. Create a virtual environment and activate it.
   - For Anaconda users:
     - Create a new environment: `conda create -n your-env-name python=3.9 pip`
     - Activate the environment: `conda activate your-environment-name`
3. Install the required libraries using `pip install -r requirements.txt`.

## Setup Instructions

1. Amend the `amadeus_api.yml` file with your Amadeus credentials.
2. Update the `configurations.json` file with your specific configurations.
3. In the `flights_tutorial_notebook.ipynb`, adjust the `configurations_path` to point to your `configurations.json`.
4. Modify the `update_tabs.py` script, specifically the `script_dir` path on line 9, to reflect the location of your `amadeus_api.yml` file.

## License

This work, based on "Auto Gen Flights Tutorial" by John Adeojo from Data-centric Solutions, is utilized and adapted under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

## How to Credit

When using or adapting this work, please credit as follows:

"Based on 'Auto Gen Flights Tutorial' by John Adeojo from Data-centric Solutions, used under CC BY 4.0 / Desaturated from original."

### Original Tutorial Citation
- John Adeojo, "Auto Gen Flights Tutorial", Data-centric Solutions. Available under a Creative Commons Attribution 4.0 International License.

