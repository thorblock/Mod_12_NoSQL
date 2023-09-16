# Mod_12_NoSQL
The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data to help their journalists and food critics decide where to focus future articles.

## Setup notes
The second Jupyter block imports the establishments' data and creates the database and collection names without a terminal. However, it's important to note that the database and collection will not appear in MongoDB until data is inserted. i.e., if you load only uk_food and establishments in python, uk_food will not appear when you check .list_database_names(). Once data is inserted with .insert_ or .update_, the database and collection will now appear when you check. 
