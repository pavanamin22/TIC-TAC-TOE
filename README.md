Tic Tac Toe - A Fun Neon Twist!
What's This All About?
Hey there! Welcome to a super cool Tic Tac Toe game that brings the classic 3x3 grid to life with a futuristic, neon-cyberpunk vibe. Built with just HTML, CSS, and JavaScript, this game lets two players duke it out by placing 'X' or 'O' symbols, aiming to line up three in a row, column, or diagonal. It's got flashy visuals, sound effects, and a score tracker to keep things exciting!
Cool Features

Play with a Friend: Take turns placing 'X' or 'O' on the grid. First to get three in a row wins!
Cyberpunk Style: Think neon lights, glowing buttons, and a sleek, sci-fi look with cyan and magenta hues.
Fun Animations: 
Cells light up with a cool scanning effect when you hover over them.
The title flickers like a neon sign.
Confetti pops up to celebrate wins or draws!
A glowing line highlights the winning combo.


Score Keeper: Tracks wins for 'X' and 'O', saved right in your browser so you can pick up where you left off.
Color Switcher: Click the ⚡️ icon to swap between awesome neon color schemes.
Sound Effects: Hear a click when you make a move, a cheer for wins, and a sound for draws (note: the audio in the code is a placeholder).
Responsive Design: Looks great whether you're on a phone, tablet, or computer.
Reset Options: Start a fresh game or wipe the scoreboard with a click.
Pop-up Messages: Get a fun pop-up when someone wins or the game ends in a tie, with a quick reset button.

How to Set It Up
Getting started is super easy:

Grab the File: Download or copy the index.html file to your computer.
No Extra Stuff Needed: The game runs on plain HTML, CSS, and JavaScript, with fonts pulled from Google Fonts online.
Audio Note: The code uses placeholder audio (base64 format). For the full experience, swap these out with real .mp3 files for click, win, and draw sounds. Just update the <audio> tags in the code.

How to Play

Start the Game: Open index.html in your web browser, and you're ready to go!
Gameplay:
Click any empty cell to place your 'X' or 'O'.
The game tells you whose turn it is and switches players after each move.
Win by getting three of your symbols in a row, column, or diagonal.
If all cells are filled with no winner, it's a tie!


Controls:
Reset Game: Clears the board for a new round.
Reset Score: Sets both players' scores back to zero and starts a fresh game.
Color Changer (⚡️): Click the lightning bolt to switch up the neon colors.


Pop-up: Shows up when someone wins or it's a draw, with a handy reset button.
Scoreboard: Keeps track of wins for 'X' and 'O', saved so you can keep the rivalry going.

Running the Code
Here's how to get the game up and running:

Save the File: Store index.html somewhere on your computer.
Open It:
Just double-click index.html to open it in your browser (Chrome, Firefox, etc. work great).
For a smoother experience, you can run a local server:python -m http.server 8000

Then visit http://localhost:8000 in your browser.


Fix the Audio: The code has placeholder audio. To use real sounds:
Replace the <source> tags in the <audio> elements with paths to your .mp3 files, like:<audio id="click-sound" preload="auto">
    <source src="sounds/click.mp3" type="audio/mpeg">
</audio>


Make sure your audio files are in a sounds folder next to index.html (or adjust the path).


Browser Tips: Works best in modern browsers with JavaScript enabled. If sounds don't play, check the console for errors (the placeholder audio might not work everywhere).
Hosting Option: Want to share it? Pop index.html onto a web server (like Apache or Nginx) for others to play online.

A Few Things to Know

The "Open New Game" button was left out, as requested.
No background particle effects are included, keeping things clean but still flashy with confetti for wins and ties.
The color changer picks from a set of neon color combos for a consistent, cool look.
If the audio doesn't work, it might be the placeholder data. Swapping in real .mp3 files should fix it.

Have fun playing, and may the best player win! 🎮
