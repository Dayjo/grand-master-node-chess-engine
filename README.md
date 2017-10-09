# GrandMaster node-chess-engine
Chess engine node module taken from https://github.com/nmrugg/stockfish.js to allow easy installation and use from remote server.

I wanted to be able to run stockfish on a variety of servers namely through PHP. Turned the existing example node module into an NPM module for ease of use.

# Installation
```shell
npm install -g grand-master
```

# Use
```shell
grandMaster g1f3 e7e5
```

## Functionality
Calculate Computer's Move (stockfish.js) given a FEN or set of moves.


## Todo;
- [ ] Re-write / cleanup the node server
- [ ] Set AI difficulty level.
