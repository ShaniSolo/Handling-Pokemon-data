#Pokemon Project - Handling Pokemon data
This exercise is built on a sql database, that migrates Pokémon data into a DB and define queries over the DB. and continues by building a Pokémon API using Flask.

###About
PokeCorp is a company that tracks Pokémon and their trainers around the world. Each Pokémon has some data, as well as an ownedBy field.

The ownedBy field is an array of objects, where each object represents a trainer that owns this pokemon.

###To conclude:

These are the SQL tables :


* pokemon
* types
* trainer
* ownership

These are the routes :

* Update Pokémon types
* Add Pokémon
* Get Pokémon by type
* Get Pokémon by trainer
* Get trainers of a Pokémon
* Evolve (pokemon x of trainer y)
* delete pokemon of trainer
###usage
* At first - run the pokemon_tables.sql file to create the tables. 
* Then run the insert_data.py to insert the data
* At least - run the server by the main.py to create a port.
* now you can use the queries and test the project

###Database Link
[pokemon data](https://pokeapi.co/)
