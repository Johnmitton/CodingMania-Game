# CodingMania-Game
The goal of this group project is to design, implement, test, and evaluate an arcade-style 2D game managed and built in Apache Maven. The player controls the main character from the start point to the end point through barriers and the enemies on the board.

The main character should collect the rewards that are placed at various places on the map. The score of the player, which is the accumulation of all rewards, and the playtime are shown on the screen. The player wins by reaching the "exit" cell after collecting all "regular" rewards on the board. The player loses if the main character encounters or is caught by a moving enemy, or the overall score becomes negative. Each moving character can move at most one cell at each \tick" of the game, as described below.

See Project-Phase1,2,3, and 4 for more detail.

How to Run:
1. from the project directory locate the game directory
2. change directory to project/game/
3. from the game directory
4. run the command "mvn clean install"
5. Play the game using one of the following

        5.1 - run the command "java -cp target/game-1.4.jar com.group2.App"

        5.2 - open file explorer and locate the project folder, change working directory to project/game/target and open game-1.4.jar by double clicking

6. to create and view javadocs

        6.1 - run command mvn javadoc:javadoc
    
        6.2 - change working directory to project/game/target/site/apidocs
        
                6.2.1 - for javadoc for all classes locate and open allclasses-index.html
        
                6.2.2 - for javadoc for all packages locate and open allpackages-index.html
enjoy!
