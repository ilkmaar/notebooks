# Concord Ilkmaar Game Data Science Notebooks

This repository contains Jupyter notebooks for the "Isles of Ilkmaar" project, a data-rich multiplayer virtual world designed to promote middle school-aged girls' interest in data science.

## Project Overview

The Isles of Ilkmaar is a three-year Innovations in Development project led by the Concord Consortium in partnership with the University of Miami and FableVision Games. The project aims to promote data science interest among middle school girls through an identity-aligned, social game-based learning approach.

The virtual world enables players to:
- Collect resources across different islands
- Craft items from collected resources
- Interact with creatures in the game world
- Build relationships with creatures through gifting and interactions
- Analyze game data to make strategic decisions

## Notebook Contents

This repository contains various notebooks used for development, data exploration, and game simulation:

### Database Setup & Management
- `database_metadata.ipynb` - Database schema definitions and table creation
- `database_user_setup.ipynb` - User permissions and access configuration
- `mysql_python_connector.ipynb` - Connection examples using Python to MySQL
- `populate_database.ipynb` - Scripts to populate the game database with initial data

### Data Exploration & Analysis
- `data_prototyping.ipynb` - Early data modeling and prototyping
- `data_views.ipynb` - View and query data in various ways
- `visualization_explorations.ipynb` - Visualization examples for game data

### Game Simulation
- `simulate_gameplay.ipynb` - Scripts to simulate player behavior in the game world
- `danny_data.ipynb` - Additional gameplay data analysis

### AI Integration
- `Ilkmaar_AI.ipynb` - RAG-based system for querying PDFs related to the project
- `gpt_query.ipynb` - Integrating GPT models for game content and analysis

### Data Querying
- `sample_queries.ipynb` - Examples of useful data queries for game analysis

## Database Structure

The game uses a relational database with the following key entities:
- Players
- Creatures
- Resources/Items
- Locations
- Collections (inventories)
- Events (crafting, gifting, interactions)

The database is designed to capture all player activities and interactions to support data science learning.

## Getting Started

To use these notebooks:

1. Ensure you have access to the Google Cloud project
2. Set up authentication to Google Cloud within the notebooks
3. Install required Python packages:
   ```
   pip install cloud-sql-python-connector["pymysql"] SQLAlchemy pandas gspread
   ```
4. Run the database setup notebooks first if creating a new instance

## Data Science Learning Opportunities

The project incorporates multiple "purpose pathways" for working with data:
- Analyzing creature behavior and preferences
- Optimizing resource collection and crafting
- Examining social relationships in the game
- Visualizing player progress and strategies

## Project Goals

This project addresses the underrepresentation of women, particularly Latina women, in data science fields by:
1. Creating identity-aligned experiences with data
2. Providing social, collaborative data work
3. Making data science relevant to middle school girls' interests and goals
4. Supporting multiple purpose pathways for working with data

## License

See the LICENSE file for details.