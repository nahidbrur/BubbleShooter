# BubbleShooter
Bubble Shooter is a simple interactive game. The goal of the game is to clear the playing field by forming groups of three or more like-colored marbles. The game ends when the balls reach the bottom line of the screen. The more balls destroyed in one shot, the more points scored. A player wins when there are no balls remaining on the playing field. I developed this game using the below tools for a study of openGL:

1. OpenGL
2. C++

For detail descriptions please see [technical.pdf](technical_doc.pdf)

## Environment Setup and run the game on linux
1. First install necessary packages using 

    ```sudo apt-get install freeglut3 freeglut3-dev mesa-common-dev```

2. Then build the cpp file using

    ```g++ -o bubble_shooter bubble_shooter.cpp -lglut -lGLU```
  or

    ```g++ -o bubble_shooter.out bubble_shooter.cpp -lglut -lGLU -lGL```

3. Finally double click on `bubble_shooter.out` and enjoy the game
