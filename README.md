# README
A re-creation of the timeless classic, **Pong!**. Challenge a computer-controlled opponent in this endless tennis-style game. Test your reflexes and timing as you attempt to outscore the AI in this addictive back-and-forth battle.

![pong](https://github.com/user-attachments/assets/c8f14d2f-6fba-4ab4-945c-7ae0ac2d32e1)

# How to Play

1. **Run the Game**: Open your terminal and type `python3 main.py` to start the game.
   
2. **Controls**:
   - **Up/Down Arrow Keys**: Use the Up/Down arrow keys to move your paddle up/down.

3. **Objective**: 
   - Hit the ball back and forth across the screen
   - Score points when your opponent misses the ball
   - No score limit - play as long as you want!
   - Game progress automatically saves

4. **How to reset the score**:
   - To reset the score, you must delete the 'score.txt' file in the 'data' folder.

### Future implementation:
   - <s>Background music integration</s>
   - GUI and menu
   - Multiplayer mode for local 2-player matches
   - Difficulty settings for the AI opponent
   - Power-ups that modify ball speed or paddle size
   - Visual and sound effect improvements
   - High score leaderboard
   - Different paddle and ball skins
   - Game modes (time attack, first to 10, etc.)

## Lessons Observed in the Project:
   - ### Technical Skills:
      - Implemented game loop and frame rate management
      - Implemented collision detection between ball and paddles
      - Utilized JSON for saving/loading game state
      - Managed scoring system with persistent data
   
   - ### Game Development Concepts:
      - Score tracking and persistence
      - Game state management

   - ### Tools & Frameworks:
      - Practical experience with the Pygame library
      - JSON for data persistence
      - Version control

## Additional Notes
The project successfully recreates the core Pong experience while adding modern conveniences like game saving. Its simple but addictive gameplay makes it an excellent foundation for future enhancements. 
