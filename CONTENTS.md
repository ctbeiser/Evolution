evolution/action.py
	Contains the representations of all possible player actions with Trait Cards
evolution/action4.py
	Contains the representation of all requested player actions for a turn
evolution/dealer.py
	Contains a representation of the Dealer in the game
evolution/debug.py
	Contains functions useful for logging
evolution/feeding_intent.py
	Contains all possible feeding intents returnable by Player
evolution/gui.py
	Contains a script that produces GUIs from dealers and players.
evolution/json_socket.py
	A wrapper around a TCP socket that translates its input and output into JSON
evolution/player.py
	Contains a representation of Player in the game
evolution/proxy_dealer.py
    	Wrapper for client for evolution game
evolution/server.py
	Outer server for evolution game
evolution/species.py
	Contains a representation of Species boards in the game
evolution/trait.py
	Contains a representation of Traits in the game
evolution/traitcard.py
	Contains a representation of Trait Cards in the game
evolution/timeout.py
    Timing utility decorator
evolution/validate.py
    Validation utilities

Tests:
evolution/test_actions.py
	Tests for actions.py
evolution/test_dealer.py
	Tests for dealer.py
evolution/test_feeding_intent.py
	Tests for feeding_intent.py
evolution/test_player.py
	Tests for player.py
evolution/test_species.py
	Tests for species.py

main.py
	Starts the server to play the game
player.py
	Starts a player to play a game
main
	A bash script that starts a game with five players
compile
	Exits with code 0
test_main.py
	Tests utility functions inside main.
