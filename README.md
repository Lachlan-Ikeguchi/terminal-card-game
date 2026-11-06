# Terminal Card Game (TCG)
## Goal
A single player card game played in the terminal with support for various games called by a flag `$ tcg --transfer-durak` etc.

The UI is REPL style with a prompt and various commands available to interact with your own deck and to see available information.

To be extendable, the `tcg` binary shall be an engine that runs lua scripts which provide the game logic and rules.
