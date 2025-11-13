# Valorant Discord Bot
![alt text](https://github.com/Dhruvbam/Valorant-Discord-Bot/blob/main/Images/valo.jpg)

Developed in just 24 hours at Hackwest 2023, Valorant Discord Bot is a cloud native Python app optimized for Valorant’s 25M+ global players. Purpose built for Discord integration, this bot leverages Python, Flask, and Google Cloud Platform to deliver uninterrupted, 24/7 support with real time agent selection, tactical roulette, personalized map and agent tips, and rank based shooting advice. Seamless backend architecture and dynamic database querying ensure instant, reliable access to strategic recommendations that elevate competitive FPS gameplay. By combining scalable Google cloud deployment, secure API connections, and performance analytics into a single tool, the project illustrates both technical depth and a keen focus on impactful real world problem solving.

## Built With
- <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" width="36" height="36" alt="Python" /></a> **Python**: Core programming language used for bot development.
- <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" width="36" height="36" alt="Flask" /></a> **Flask**: Web framework used to create the backend server.
- <a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" width="36" height="36" alt="GCP" /></a> **Google Cloud Platform (GCP)**: Deployed the backend for global access.
- - **YAML**: Used for specifying Python 3.9 runtime and deployment configuration on Google Cloud Platform.
- **PyMySQL**: Used to interact with the SQL database containing information on agents, maps, and strategies.
- **PyNaCl**: Provides cryptographic support for secure communication between Discord and the bot.

## Features & Technical Details
- **Real-Time Agent and Strategy Selection:** Instantly picks random agents and strategies for players, increasing variability and teamwork in matches.
- **Map and Agent Tips:** Provides actionable, map-specific and agent-specific guidance, improving in-game decision-making and support for all skill levels.
- **Performance-Tuned Shooting Advice:** Delivers custom shooting tips based on competitive rank, helping players refine aim through focused analytics.
- **Cloud-Native Deployment:** Python and Flask backend deployed on Google Cloud Platform ensures low-latency, high-availability global operation.
- **Database-Driven Intelligence:** PyMySQL secured connection to remote SQL database powers live data retrieval for agents, maps, and ranked tips.
- **Discord API Integration:** Streamlines communication for instant bot command execution, with cryptographic security via PyNaCl.
- **Scalable Event-Driven Architecture:** Designed to handle concurrent user requests and deliver consistent outputs, even under peak server loads.


## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/valorant-discord-bot.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up the environment variables for Flask and Discord, including your Discord bot token and public key.
4. Run the Flask app:
    ```bash
    python main.py
    ```

### Usage
1. Invite the bot to your Discord server.
2. Use the following commands to interact with the bot:
    - `/agent`: Selects a random agent.
    - `/stratroulette`: Chooses a random strategy for the team.
    - `/maptips`: Provides tips for the selected map.
    - `/agent_tips`: Offers tips for a selected agent.
    - `/shootingtips`: Gives shooting tips based on your rank.

## Contributions / References
This project was collaboratively developed by:
- **Dhruv Maniar**
- **Isha Koregave**
- **Suchit Pinreddy**
- **Vedant Supnekar**

## Screenshots / Demo
Watch Video: </br>
[![Watch the video](https://github.com/Dhruvbam/Valorant-Discord-Bot/blob/main/Images/valo.jpg)](https://github.com/Dhruvbam/Valorant-Discord-Bot/blob/main/Images/RPReplay_Final1677425932.MP4)

