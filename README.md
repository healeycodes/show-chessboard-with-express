### Show Chessboard With Express

This is an ongoing experiment to create a general-use chess board representation API (i.e., something that returns images).

Currently it's an example of a Node.js/Express/EJS wrapper around chessboard.js.

![alt text](https://github.com/healeycodes/show-chessboard-with-express/blob/master/public/img/example-board.png "chessboard.js")

There are two routes, both of which accept a FEN string and return a page containing a chessboard.js representation of the FEN string in HTML/CSS/JavaScript. GET uses params, POST uses JSON.

#### GET /api/fen/ `<FEN String>`

#### POST /api/fen/ `{"fen":"<FEN String>"}`

&nbsp;

### Tech Stack
Node.js/Express with EJS templates, chessboard.js.

&nbsp;

### Install

```npm install```

### Run

```node .\server.js```

### Tests

Tested with Jest and SuperTest.

```npm test```
