# HackTheNorth2018
Hideaway MTG Deckbuilder: https://devpost.com/software/cards101
This was my group's submission for the HackTheNorth hackathon this year.
"Browse over 18000 (MTG) cards with efficiency, beauty, and detail."

# What it does
We built an API for making TCG applications, which allows future developers to create deck builders, games, and many more creative applications. Using that API, we also made a MTG deck editor. This allows users to log in / register, get all the cards, their descriptions and images. The deck editor allows them to create, remove, and save decks. The deck editor was made using python (pygame graphics). It connects to a web server running the API, made using Flask, to retrieve card and account information.

# Where is the complete project?
The code posted here is the client, made by me and Anish Aggarwal (https://github.com/aaggarwal10). It connects to our datebase (web server), which was made by James Xu (https://github.com/jamesxu123). Running this code will not work unless his server is up. 

# Which parts did you make?
I set up the outline for our client-server interactions, made the backend of the client, designed our front end, and worked with Anish on the front end.
