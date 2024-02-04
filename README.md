# ICC Cricket Manager

This is a simple Cricket System implemented in C++. The system allows users to manage cricket teams, conduct matches, and schedule upcoming matches. It includes features like adding and removing players, searching and updating player information, and updating team captain and coach.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Features](#features)
- [Classes](#classes)
- [License](#license)

## Prerequisites
Before running the application, ensure you have a C++ compiler installed on your system.

## Usage
1. Clone the repository to your local machine.
2. Open the project in a C++ IDE or compile using a C++ compiler.
3. Run the executable file generated after compilation.

## Features
- **Access Team Menu:**
  - Add Player
  - Remove Player
  - Search Player
  - Update Player
  - Display Matches
  - Update Captain
  - Update Coach

- **Main Menu:**
  - Access Team
  - Add Team
  - Conduct Match
  - Schedule Match
  - Exit

## Classes
1. **Player Class:**
   - `add_Player`: Adds a player to a specific team.
   - `remove_Player`: Removes a player from a specific team.
   - `search_Player`: Searches for a player in a specific team.
   - `update_Player`: Updates player information in a specific team.

2. **Team Class:**
   - `add_Player`: Adds a player to a specific team.
   - `remove_Player`: Removes a player from a specific team.
   - `add_team`: Adds a new team.
   - `search_Player`: Searches for a player in a specific team.
   - `update_Player`: Updates player information in a specific team.
   - `update_Captain`: Updates the captain of a specific team.
   - `update_Coach`: Updates the coach of a specific team.
   - `display_Team`: Displays players of a specific team.

3. **Match Class:**
   - `conductMatch`: Conducts a match and updates team rankings.
   - `scheduleMatch`: Schedules a match and updates the schedule file.
   - `updateTeamRanking`: Updates team rankings based on match results.
   - `sortAndUpdate`: Sorts team rankings and updates the rankings file.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the terms of the license.
