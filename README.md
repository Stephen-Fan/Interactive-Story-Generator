# Interactive Story Generator

An interactive story generator built with **React** and **FastAPI**, deployed on **Choreo**. Data is managed in SQLite databases.  
It integrates the **OpenAI API** to generate complete, branching storylines at once, allowing users to explore different paths and endings based on their choices.

---

## Features

- **AI-Generated Stories:** The ChatGPT API creates a full story tree with multiple branches and endings based on a selected theme.  
- **Interactive Exploration:** Users navigate through pre-generated story branches by making choices at key decision points.  
- **Responsive Frontend:** Built with React for a seamless, real-time storytelling experience.  
- **Cloud Deployment:** Backend hosted and managed on Choreo for scalability and stability.

---

## Tech Stack

- **Frontend:** React (Vite)  
- **Backend:** FastAPI (Python)  
- **AI Integration:** OpenAI ChatGPT API  
- **Deployment:** Choreo  
- **Version Control:** Git + GitHub

---

## How It Works

1. The user selects a story theme (e.g., fantasy, mystery, sci-fi).  
2. The backend requests the ChatGPT API to generate the **entire branching storyline**, including all possible choices and endings.  
3. The full story structure is returned to the frontend.  
4. As users make choices, the UI reveals the corresponding branches from the pre-generated story tree. No further API calls are needed.  
5. Users can replay the story and explore alternate paths instantly.

