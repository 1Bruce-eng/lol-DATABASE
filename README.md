# League of Legends (LoL) Game Data Management System

## Project Overview

This project is a League of Legends game data management system designed to store and manage various game-related data, including champions, items, players, matches, and more.

## Database Structure

The database contains the following main tables:

1. **champion** - Champion Information Table
   - Stores basic champion information
   - Includes champion ID, name, role, base attributes, etc.

2. **item** - Item Information Table
   - Stores game equipment information
   - Includes item ID, name, cost, attribute bonuses, etc.

3. **player** - Player Information Table
   - Stores player account information
   - Includes player ID, summoner name, ranked tier, etc.

4. **match** - Match Information Table
   - Records game match information
   - Includes match ID, start time, duration, etc.

5. **Related Tables**
   - itembuilditems (Item build details)
   - playerskin (Player owned skins)
   - matchparticipant (Match participant details)
   - team (Team information)

## Views

The system includes the following views:

1. **champion_combinations** - Champion combination statistics
2. **itembuildpopularity** - Item build popularity statistics
3. **playerchampionstats** - Player champion performance statistics

## Main Features

1. Champion Management
   - View champion information
   - Track champion usage statistics

2. Item System
   - View item attributes
   - Analyze build paths

3. Player Data
   - Record player information
   - Track player performance

4. Match Records
   - Store match data
   - Analyze game performance

## Tech Stack

- Database: MySQL 10.4.32-MariaDB
- Character Set: utf8mb4
- Collation: utf8mb4_general_ci

## Notes

1. Pay attention to foreign key constraints when performing database operations
2. Ensure data integrity and consistency
3. Regular database backups are recommended

## Contributors

- Group-11 Team Members
