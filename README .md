# 🌍 WanderWise-Agent

## 🤖 The Ultimate AI Travel Planner

WanderWise-Agent is an intelligent, autonomous system designed to revolutionize travel planning. Using advanced AI and large language models (LLMs), it generates personalized itineraries, manages bookings, and provides real-time destination insights based on user preferences and constraints.

---

## ✨ Features

* **Personalized Itineraries:** Generates day-by-day travel plans based on interests, budget, and travel style.
* **Real-Time Recommendations:** Suggests restaurants, activities, and local events dynamically.
* **Cost Estimation:** Provides budget forecasting and tracks expenses.
* **Multi-Platform Integration:** [Specify any APIs or services it connects to, e.g., Google Maps API, flight booking services].

---

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need the following installed:

* **Python** (version 3.8 or higher)
* **pip** (Python package installer)
* A valid **OpenAI API Key** (or another LLM provider key)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AP24110011714/WanderWise-Agent.git](https://github.com/AP24110011714/WanderWise-Agent.git)
    cd WanderWise-Agent
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up your environment variables:**
    * Create a file named `.env` in the root directory.
    * Add your API key inside the `.env` file (***NOTE: This file is ignored by our included `.gitignore` for security.***):
        ```
        OPENAI_API_KEY="YOUR_SECRET_KEY_HERE"
        ```

### Running the Agent

To start the WanderWise Agent:

```bash
python main.py
