Inkball Project：
This is a Java-based game project called Inkball, where players control the movement of balls within a set boundary, capturing them in the correct sequence while avoiding obstacles. The game focuses on physics-based movement and timing, offering challenging gameplay mechanics.

Table of Contents
Introduction
Installation
Usage
Features
Configuration
Contributing
License
Contact
Introduction
Inkball is a physics-based game developed in Java, where players must guide multiple balls into their respective goals using drawn lines. The game features several levels with increasing complexity, introducing new obstacles and mechanics as players advance.

Installation
To get started with this project, follow these steps:

Clone the repository:

git clone https://github.com/hym-fei/inkball-java.git
cd inkball-java
Install dependencies:

Ensure you have Java installed on your system. You can verify this by running the following command:

java -version
Compile the project:

Use a Java compiler (e.g., javac) to compile the source code. Navigate to the src directory and run:

javac -d bin src/com/inkball/*.java
Run the game:

After compiling, run the game with the following command:

java -cp bin com.inkball.Main
Usage
Once the game is running, players can draw lines with the mouse to direct the balls into the correct goals. The game includes different levels with distinct colored balls and goals. The objective is to guide the balls to matching-colored goals while avoiding obstacles.

Features
Physics-based gameplay: Realistic ball movement and interactions.
Java AWT/Swing UI: Uses Java's AWT/Swing framework for drawing and handling player interactions.
Level-based progression: Multiple levels with increasing difficulty.
Player-drawn interaction: Players draw paths for the balls to follow.
Ball-color matching: Balls must be directed into matching-colored goals.
Obstacles and hazards: New elements such as barriers and traps are introduced in higher levels.
Configuration
The game's configuration is stored in the config.json file, where you can adjust various aspects such as:

Time limits per level
Spawn intervals for balls
Score modifiers for successful captures
Ball color sequences for each level
To modify the configuration, simply edit the config.json file located in the project directory.

Contributing
We welcome contributions! If you'd like to contribute to the Inkball project, please follow these steps:

Fork the repository
Create a new feature branch (git checkout -b feature-name)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature-name)
Open a pull request
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any inquiries, please contact 15867728699@163.com.

