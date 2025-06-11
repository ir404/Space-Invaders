# Space-Invaders
A recreation of the infamous arcade game - Space Invaders!

By building this project I learnt a little about 
- pixel art (yes, the spaceship image and alien ships were designed by me)
- box collision

![SpaceInvaders](https://user-images.githubusercontent.com/67403229/125967460-9f912b84-d7d9-4803-aa26-16a585cf071c.gif)

## Playing the Game
1. Download and set up a JDK (version 17+)
   1. If you're on Windows, it's a good idea to add it to your PATH environmental variable
2. Download JavaFX 21 SDK according to your OS ([link](https://gluonhq.com/products/javafx/))
   1. Take note of path to the `/lib` directory. For example: `C:\Program Files\Java\JavaFX\javafx-sdk-21.0.7\lib`
3. Clone this repository 
4. Open the project directory in the terminal/command prompt
5. Run the following command to compile the project:
   1. `javac --module-path "C:\Program Files\Java\JavaFX\javafx-sdk-21.0.7\lib" --add-modules javafx.controls,javafx.graphics Game.java`
6. Next, enter the following to run the program:
   1. `java --module-path "C:\Program Files\Java\JavaFX\javafx-sdk-21.0.7\lib" --add-modules javafx.controls,javafx.graphics --enable-native-access=javafx.graphics Game`
7. Use the arrow keys to control your player, space to shoot and escape to pause/resume the game
8. FYI, the movement of your spaceship may not be very smooth but hey, its playable :)
9. Enjoy
