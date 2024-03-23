# Superhero Smart Contract

This smart contract is a superhero management application written in the Motoko language. Users can create, read, update, and delete superheroes.

## Data Structures

* `SuperheroId`: Represents the superhero ID number.
* `Superhero`: Contains the superhero's name and superpowers.

## Functions

* `create(superhero: Superhero): async SuperheroId`: Creates a new superhero and returns the ID number.
* `read(superheroId: SuperheroId): async ?Superhero`: Gets the information of a specific superhero.
* `update(superheroId: SuperheroId, superhero: Superhero): async Bool`: Updates a specific superhero.
* `delete(superheroId: SuperheroId): async Bool`: Deletes a specific superhero.

## Used Modules

* `List`: Used for list data structure.
* `Option`: Used to work with optional values.
* `Trie`: Used to store and manage key-value pairs.
* `Nat32`: Used to work with natural numbers.

## How to Use

1. Import the necessary modules to initialize the smart contract.
2. Create a trie data structure for superheroes.
3. Add, update or delete superheroes as desired.
