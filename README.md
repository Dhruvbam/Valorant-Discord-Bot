# Valorant Discord Bot
![alt text](https://github.com/Dhruvbam/Valorant-Discord-Bot/blob/main/Images/valo.jpg)

## About
Developed during Hackwest 2023, a 24-hour hackathon competition, the **Valorant Discord Bot** is a dynamic tool designed to enhance the gaming experience for Valorant players. Valorant is a popular 5v5 FPS game with over 18 million players, featuring unique agents and maps. This bot offers real-time game tracking and tips, supporting players with automated functionalities directly on Discord.

## Description
The **Valorant Discord Bot** provides various commands to assist Valorant players in improving their gameplay. Whether you're looking to randomly select an agent, choose a gameplay strategy, or get tips on maps and shooting, this bot has you covered. Developed with Python and Flask, and deployed on Google Cloud Platform (GCP), the bot integrates seamlessly with Discord to provide instant, in-game assistance.

### Features
- **/agent**: Randomly selects an agent for the player, helping to increase versatility and improve gameplay.
- **/stratroulette**: Chooses a random gameplay strategy for the team, adding an extra challenge to the game.
- **/maptips**: Provides strategies and tips for the selected map, improving the player's understanding and increasing their chances of winning.
- **/agent_tips**: Offers insights and strategies for playing as a selected agent, helping players master their chosen character.
- **/shootingtips**: Delivers shooting tips based on the player's competitive rank, aiding in improving aim and accuracy.

### Built With
- <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" width="36" height="36" alt="Python" /></a> **Python**: Core programming language used for bot development.
- <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" width="36" height="36" alt="Flask" /></a> **Flask**: Web framework used to create the backend server.
- <a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" width="36" height="36" alt="GCP" /></a> **Google Cloud Platform (GCP)**: Deployed the backend for global access.
- **PyMySQL**: Used to interact with the SQL database containing information on agents, maps, and strategies.
- **PyNaCl**: Provides cryptographic support for secure communication between Discord and the bot.

### Installation
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

### Contributions / References
This project was collaboratively developed by:
- **Dhruv Maniar**
- **Isha Koregave**
- **Suchit Pinreddy**
- **Vedant Supnekar**

### Learning Outcome
The development of the Valorant Discord Bot provided an opportunity to explore real-time game integration with Discord, using Python and Flask. The project enhanced our understanding of deploying scalable applications on cloud platforms and integrating third-party APIs to create a dynamic, user-interactive experience.

### Screenshots / Demo
[Watch the video](https://github.com/Dhruvbam/Valorant-Discord-Bot/blob/main/Images/RPReplay_Final1677425932.MP4)
