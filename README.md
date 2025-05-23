
# Trip Planner: CrewAI


## Introduction

Trip Planner leverages the CrewAI framework to automate and enhance the trip planning experience, integrating a CLI, FASTAPI, and a user-friendly Streamlit interface.



## Running the Application

- **Configure Environment**: Set up the environment variables forGemini, Serper and Browseless. Use the `secrets.example` as a guide to add your keys then move that file (`secrets.toml`) to `.streamlit/secrets.toml`.

- **Install Dependencies**: Execute `pip install -r requirements.txt` in your terminal.

- **Launch the Streamlit App**: Run `streamlit run streamlit_app.py` to start the Streamlit interface.

★ **Disclaimer**:  Need to setup Gemini, Serper and Browserless API KEY. 

## Details & Explanation

- **Streamlit UI**: The Streamlit interface is implemented in `streamlit_app.py`, where users can input their trip details.
- **Components**:
  - `./trip_tasks.py`: Contains task prompts for the agents.
  - `./trip_agents.py`: Manages the creation of agents.
  - `./tools directory`: Houses tool classes used by agents.
  - `./streamlit_app.py`: The heart of the Streamlit app.
 
 
