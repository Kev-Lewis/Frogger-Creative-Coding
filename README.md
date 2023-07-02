# Frogger - (Creative Coding)
-------------------------------------------
Instructions:

Movement:

Voice Controls -> Say "Up", "Down", "Left" or "Right"

Arrow Keys -> Up, Down, Left, Right Arrow Keys

Switch Controls -> Shift

Restart after Gameover -> Enter or say "Yes"

-------------------------------------------
Description:

A topic that we learned during this class that was really interesting was
the Machine Learning that we learned the second to last week. In particular,
the sound recognition was pretty interesting, and since I am a CSGD major, I thought
it would be interesting to use it in the context of a game. 

I thought for awhile about what games would be possible, and I decided upon Frogger as a game to implement
the voice controls since it has pretty simple controls to use as commands. In my
Machine Learning assignment, I made a chess board that could be traversed using voice
controls, so I used that as a base for the movement, then went into Illustrator to make
the art, which is not my strong point, and then put it into the grid and made sure the
movement only stayed within the grid. 

Then I added the scoring and reset to the bottom
which was pretty simple. 

Next, I designed some cars in two different colors. I added
a single car starting from the top row. I made a bunch of randomization variables
like color and orientation to make it more interesting.

The way that the car moves is
that it moves one square tile per frame update, which is 4 for arrow key controls and 1 for
voice since the voice is a little more buggy so it gives the player a more fair chance.

Also, the player can only move one tile per frame update, which prevents them from just
spamming and moving way faster than the cars. I made it scale in difficulty by making a score
threshold to increase the amount of cars that spawn at one time, starting with 1 at the
beginning, 2 after scoring 1 and incrementing to a max of 5 every 4 points after 1.

Finally, I went on Freesounds in order to get some sounds to make the game a little more
lively and polished.

-------------------------------------------
Credits:

Art: Me (Kevin Lewis)

Sounds:

hop.wav -> https://freesound.org/people/OwlStorm/sounds/404794/

score_up.wav -> https://freesound.org/people/ProjectsU012/sounds/341695/

gameover.wav -> https://freesound.org/people/ProjectsU012/sounds/333785/

-------------------------------------------
Link to project: https://editor.p5js.org/Kevin-Lewis-13/sketches/QCtGmEOHx

Portfolio Link: https://kevinlewis.net/other-projects/frogger-creative-coding
