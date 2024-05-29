### HTML Files

**index.html**:
- The landing page of the game.
- It displays a start button that triggers the game's initialization.
- It provides an area to display the game board and controls for user input.

### Routes

**main.py**:
- Contains the application logic, game state management, and route definitions.

**@app.route('/'):**
- Main route that serves the index.html page.

**@app.route('/start'):**
- Starts a new game by initializing game variables and the game board.

**@app.route('/move'):**
- Processes user input, performs the corresponding move, and updates the game state.

**@app.route('/check'):**
- Checks for completed lines and removes them from the game board.

**@app.route('/over'):**
- Determines if the game is over and displays an appropriate message to the user.