# BZFlag-Robots
<p>An AI improvent to the game "BZFlag".</p>
<h3>Installation</h3>
<p>
    Download the source code version of BZFlags from https://www.bzflag.org/downloads/. Build the VS solution file in Microsoft Visual Studios and install any dependencies as necessary. Clone or download the GitHub project https://github.com/BZFlag-Dev/bzflag-dependencies. 
</p>
<h3>Implementing the AI</h3>
<p>
  Download the .h and .cxx files from this project and place it in bzflags-2.4.18\bzflag\src\bzflag folder, replacing the original files. Open up Visual Studios and add AStarNode.h, AStarNode.cxx, AStar.h, Astar.cxx, dectree.h, and dectree.cxx into the project (basically everything except RobotPlayer files). 
</p>
<h3>What is BZFlags?</h3>
<p>BZFlags is a free online multiplayer game available on Windows, Mac, and Linux. BZFlag is a capture the flag style shooter game where the player controls a tank. It can either be played as a team game where the teams are grouped by colors or a free for all. The objective of the game is to go to an enemy base, capture the enemy flag, and return to the player’s base with the flag. When a flag is captured, the team that lost its flag will lose a point, while the team with the successful capture will gain a point.  
</p>
<h3>Language and Program</h3>
<p>This game was compiled within Microsoft Visual Studios, using C#. The original source code for the game is available <a href="https://www.bzflag.org/">here</a>.</p>

<h3>Changes made</h3>
<p>The original AI we had to modify had limited functionalities. This project was done by myself and one other team member. Here are the major changes we have implemented for this project:</p>
<ul>
    <li>A* search algorithm</li>
    <li>Alignment, Cohesion, and Separation behaviors</li>
    <li>Decision tree</li>
    </ul>
<h3>Takeaway</h3>
<p>Modifying an existing game was extremely difficult. I had to learn the structure of the original code and how each object interacts with each other. This project allowed me to put my C# programming skill into use, as well as get a small taste of what video game AI is. If I were to redo this project, I would consider different pathfinding algorithms beside A*, as well as changing the entire movement controls for this game.</p>
