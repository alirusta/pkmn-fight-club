# Pokemon Fight Club

Make something akin to Pokemon Showdown: https://pokemonshowdown.com/


## General Points:
- include pokemon types, stats and other variables that affect the resulting dmg of a skill hit?
- or if that's too much work, limit variables to types and stats
- or just types and if extra lazy let every fight result be completely random
- - that way even magikarp has a realistic chance of doing his best and winning, lol
- can music or sound be integrated at all? if too complicated drop the idea
- fetch from pokeapi and store in firebase firestore database
- include the pokedex from an earlier project as search component
- add a ladder that displays player ranking
- - ladder is a win/lose counter, the higher the win counter, the higher up the ladder
- - literally turn ladder into elo (increment by a fix number higher than 1 (z.B. 22 wie bei LoL))


##


## User Points:
- user signup and login, store user data in firebase firestore
- let each user have their own inventory of 1 - 6 fetched pokemon
- allow them to view add or remove pokemon from their inventory (like the recipe app!)
- live database to track online users, see who's online right now
- users can add other users to a friend list
- users can challenge online users to battle
- - somewhat like dassana but instead of inviting users to a project, you invite them to a fight


##


## Fight Points:
- display console log in a component for users to see what has happened
- - sort of a fight history basically
- evaluate using animations for fights or idle bopping etc.
- implement sounds maybe if it's not too aids
- - fight start sound, skill hit sound, pokemon die sound, battle end sound (win/lose)


##


## Structural Points:
- login/signup component
- home component
- search component
- inventory component
- pkmn-skill component
- pkmn-type component
- pkmn-sprite component
- (sound component) if you hate your life
- fight component / result component
- online user component
- chat component
- friendlist component
- highscore component
- console log component


##


## New Ideas:
- users should be able to choose from a set of sprites as their user avatar (see dassana project!)
- implement an accuracy roll for skill hits
- yoink interesting stuff from: https://github.com/smogon/pokemon-showdown-client/blob/master/WEB-API.md
- maybe utilize entirety of pokemon-showdown api and ditch pokeapi
- or use both databases:
- - one for all battle data etc.
- - one for sprites


##


## Extras:
- complete random quick fight
- build in a bot for people to be able to play alone
- how the fuck should players be able to fight each other?
- - research and fix if possible or workaround!
- - need pipelines for live tracking of player clicks??


##


## Ultra:
- scrap all multiplayer ideas for now
- let players only compete with "Red" who is a legendary pokemon trainer
- Red is a hard enemy, who can "read" your mind
- Make him omniscient and extremely challenging:
- - When you create your inventory, he creates his own
- - Depending on what pokemon you chose, he will choose superior ones
- - For example: You pick Charizard and he picks Blastoise
- - He will basically see the type of your pokemon and choose a type yours is weak against


##


## Encountered Bugs:


##


## Bug Fixes:


##


## Dropped Ideas:

