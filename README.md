# CodSoft-Internship-Projects

This repository features three engaging projects: an AI Chatbot, a Tic Tac Toe Game with AI Opponent, and a Movie Recommendation System. Each project demonstrates different aspects of artificial intelligence and data science, utilizing techniques such as NLP, heuristic-based decision-making, and recommendation filtering.

# Table of Contents:
1. **Project Overview**
2. **Features**
3. **Setup and Installation**
4. **Usage**
5. **Project Details**
6. **Acknowledgments**

# Project Overview
- ## AI Chatbot
The chatbot is a class-based Python script with customizable personality, mood, and memory, providing users with an interactive, personalized conversation experience. It can tell jokes, provide compliments, motivate users, and even play a guessing game.

- ## Tic Tac Toe Game with AI
A Python implementation of Tic Tac Toe with an AI opponent using the Minimax algorithm with Alpha-Beta pruning. The AI's difficulty can be adjusted, providing a fun yet challenging game experience.

- ## Movie Recommendation System
This interactive recommendation system allows users to filter movies by specific attributes and get recommendations based on similarity to a selected movie. It leverages the tmdb_5000_movies.csv dataset, providing options to normalize and filter by attributes such as genres, popularity, and keywords.

# Features

1. **AI Chatbot**
   - **Personalized Interaction**: Remembers the user's name and can adjust its personality (friendly, funny, formal) and mood (happy, neutral, sad).
   - **Advanced Conversational Logic**: Includes responses to greetings, compliments, jokes, and motivation.
   - **Interactive Game**: Can play a guessing game with users.
   - **Date and Time**: Provides current date and time information.

2. **Tic Tac Toe Game with AI**
   - **Adjustable Difficulty Levels**: Choose between Easy, Medium, and Hard, with AI mistakes based on the difficulty level.
   - **Smart Move Selection**: Utilizes Minimax with Alpha-Beta pruning for efficient and challenging gameplay.
   - **User Choice of Turn**: Users can decide whether to go first or let the AI start.

3. **Movie Recommendation System**
   - **Filtering by Attributes**: Offers filtering options for attributes like vote count, revenue, runtime, genres, and keywords.
   - **Data Normalization**: Utilizes normalization functions to standardize numerical attributes.
   - **JSON Parsing**: Handles JSON-formatted columns for genres and keywords, providing accurate filtering and recommendation results.


# Setup and Installation
## Clone the Repository
- git clone https://github.com/Yuvraaj14/CodSoft-Internship-Projects.git

## Install Dependencies
- Ensure you have Python 3.7+ installed.
- Install required libraries:

    pip install -r requirements.txt
- For the Movie Recommendation System, download tmdb_5000_movies.csv and place it in the project directory or update the path in the code.

# 3. Run Each Project
- **AI Chatbot:** Run interactive_conversation() in chatbot.py.
- **Tic Tac Toe Game with AI:** Run tic_tac_toe_game() in tic_tac_toe.py.
- **Movie Recommendation System:** Run interactive_movie_system() in movie_recommendation.py.

# Usage

1. **AI Chatbot**
   - Start the chatbot using interactive_conversation().
   - Follow the prompts for a conversation and interact by typing responses.
   - Type "exit" to end the session.

  
2. **Tic Tac Toe Game with AI**
   - Start the game using tic_tac_toe_game().
   - Choose your difficulty level and turn order.
   - Enter your moves as indicated (0-8 for board positions).

  
3. **Movie Recommendation System**
   - Start the system using interactive_movie_system().
   - Select filters for movie attributes or input a movie title for recommendations.
   - Follow prompts to view results or refine selections.
  
# Project Details
1. **AI Chatbot**
   - **Technologies:** Python (Regex, datetime, and random library).
   - **Purpose:** Provide personalized, conversational interaction with varied personality and mood options.
   - **Key Features:** Personality and mood memory, guessing game, joke telling, date and time info.
  
2. **Tic Tac Toe Game with AI**
   - **Technologies:** Python (Minimax with Alpha-Beta Pruning).
   - **Purpose:** Provide an engaging Tic Tac Toe game with intelligent AI moves.
   - **Key Features:** Difficulty levels, intelligent AI moves, interactive board display.
  
3. **Movie Recommendation System**
   - **Technologies:** Python (Pandas, JSON handling).
   - **Dataset:** tmdb_5000_movies.csv.
   - **Purpose:** Interactive movie recommendation system with attribute-based filtering.
   - **Key Features:** Attribute filtering, JSON parsing, normalization of key metrics.
  
# Acknowledgments
- **TMDB Dataset:** Data source for movie information.
- **Python Documentation:** For extensive support on libraries and best practices.
