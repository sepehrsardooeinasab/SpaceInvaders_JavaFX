# Space Invaders

An implementation of Space Invaders using JavaFX library.

You can use the following command to run the jar file.

<pre>java --module-path ${PATH_JAVAFX_SDK}/lib --add-modules javafx.controls,javafx.fxml,javafx.swing -jar ${PATH_JAR_FILE}</pre>

Java version **11.0.6** and JavaFX version **11.0.2** was used.

## How to play

<kbd>&#8592; &nbsp; &#8594;</kbd> &nbsp; Move to left and right

<kbd>Space</kbd> &nbsp; Fire

## Stages

### Select Profile
In this stage, you can create a new profile or delete an older one, also the time players have spent on the game and their highest score are shown.

<img src="Images/SelectProfile.png">

### Choose difficulty
In this stage, you can choose the difficulty of the game. The health of enemies and also their fire rate changes depending on the difficulty you select. You get more points from killing enemies on harder difficulties which can help you get a higher score. 

<img src="Images/ChooseDifficulty.png">

### Loading Screen
Show "loading" for 3 seconds 😀.

<img src="Images/LoadingScreen.png">

### Gameplay
A player starts with 3 hearts and must kill all invaders to win. If the player loses all of their hearts or the invaders reach to player's spaceship, the player will lose.

Multiple obstacles are implemented. They block your bullets but they will break if they got shot 5 times.

A UFO, which is faster than the invaders and flies above them, is implemented. Defeating it gives a huge amount of points.

On the right side of the screen, you can see the number of remaining hearts, the time you spend and your current score.

<img src="Images/GamePlay.png">

### Win or lose
Show you won or lost for 3 seconds. 😇

<img src="Images/WinOrLose.png">