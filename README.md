# Valorant Match Analyzer

Analyze your recent Valorant matches using HenrikDev API, Streamlit, and Python.

This dashboard pulls your match history and performance stats, presenting it in an interactive, user-friendly format.

---

## Features

- Pulls recent Competitive matches (customizable by user)
- Displays K/D Ratio, Damage Made, Damage Received
- Visualizes performance trends with Line and Bar charts
- Displays Current Rank and Rank Badge
- Match Overview Table with win/loss highlights
- Secure API Key management with `.env` file

---

## Tech Stack

- Python
- Streamlit (Dashboard)
- Pandas (Data handling)
- Altair (Data visualization)
- HenrikDev Valorant API

---

## Setup Instructions

1. Clone the repository:

   git clone https://github.com/YourUsername/Valorant_Analyzer.git
   cd Valorant_Analyzer

2. Install the dependencies:

   Pip install -r requirements.txt

3. Create a .env file and add your HenrikDev API key:

   API_KEY=your_henrikdev_api_key_here

4. Run the application:

   streamlit run Valorant_Analyzer.py

## Future Improvements

-Add match-by-match deep analysis
-Add agent performance summaries
-Add win streak detection and statistics
-Add historical tracking for long-term trends

## Important Notes

-API key is kept hidden using a .env file (already configured in .gitignore).
-Data is retrieved using HenrikDev Valorant API for educational purposes.
-Make sure to check API usage limits and terms.

## Author

Developed by Dathwik Kollikonda