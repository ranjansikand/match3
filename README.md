# match3
A recreation of the classic tile matching game. This code will run the game, but requires LOVE2D to be opened. 

The following video depicts the final result: https://m.youtube.com/watch?v=Ayu0lkP5PsM&t=15s

Using the code from Colton Ogden, I have added the following features:
  - Valid moves are those that result in a match, otherwise the blocks shift back and an error sound plays
  - Powerup blocks that clear rows or columns
  - If no moves are available, the board automatically reshuffles
  - Securing a match adds time to the clock
  - Patterned blocks give higher point totals; the higher the level, the higher the total
