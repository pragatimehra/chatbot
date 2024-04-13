# gemini-pro-streamlit-chatbot

This repository is about building a chatbot using Google's Gemini-Pro with streamlit.

### Creating the ChatBot

This guide details the steps to set up, develop, and deploy a ChatBot using Streamlit and the Gemini Pro API.

**Prerequisites:**

* Python 3.11
* conda
* Streamlit
* PyCharm (or your preferred IDE)

**Steps:**

1. **Create Project Environment:**
    - Create a folder named `ChatBot`.
    - Create a file named `requirements.txt` to store project dependencies (add libraries later).
    - Open a terminal window and navigate to the `ChatBot` directory.
    - Deactivate any existing conda environment (if applicable): `conda deactivate`
    - Create a new conda environment named `venv` with Python 3.11: `conda create -p venv python=3.11 -y`
    - Activate the newly created environment: `conda activate venv`

2. **Install Dependencies:**
    - Install required libraries using `pip install` (list dependencies in `requirements.txt` and run `pip install -r requirements.txt`).

3. **Obtain Gemini Pro API Key:**
    - Visit the Google AI Platform ([https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)) and create an API Key.
    - Save the API Key securely in a `.env` file.

4. **Develop the ChatBot:**
    - Use PyCharm (or your preferred IDE) to write the ChatBot application code in Python.

5. **Run the App Locally:**
    - In the terminal, navigate to the `ChatBot` directory.
    - Run the app using Streamlit: `streamlit run app.py`

6. **Deploy the App:**
    - Visit Streamlit Sharing ([https://share.streamlit.io/](https://share.streamlit.io/)) and create a new app.
    - Choose to deploy from a GitHub repository.
    - Select the desired repository, branch, and main file path (`app.py`).
    - Set a custom URL for your app.
    - In the Advanced Settings, add an environment variable `GOOGLE_API_KEY` with your actual API Key.
    - Click "Deploy" to make your ChatBot accessible online.

**Note:**

- Replace your actual Gemini Pro API Key with `<your-api-key>` while pushing the code to GitHub for security best practices.


### Screenshot (Deployed on Streamlit)
![Screenshot 2024-04-13 at 2 10 53 AM](https://github.com/pragatimehra/chatbot/assets/92671158/b27828f1-4182-4315-b57d-711a3a788d0b)
