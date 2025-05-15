# cop3502-gatorraider-project-solved
**TO GET THIS SOLUTION VISIT:** [COP3502 GatorRaider Project Solved](https://www.ankitcodinghub.com/product/cop3502-gatorraider-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;77815&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3502   GatorRaider Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Overview

This project will provide students with practice working with inheritance and polymorphism in programming languages. “GatorRaider” is a game whose play and levels are based on Ms. Pac-Man. In this game, four defender characters (other lousy mascots) attempt to limit the damage by an attacker character (gator). Each student will be building a controller for the attacking character. This controller will have the following specification <strong><u>which</u> <u>students are required to follow (which is already done for you)</u></strong>:

&nbsp;

Package:&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>edu.ufl.cise.cs1.controllers</strong>

Class Name: <strong>StudentAttackerController</strong>

Implements: <strong>AttackerController</strong>

&nbsp;

<h1>Getting the Code Base</h1>
This project requires students to work in an existing code base. You will need to download the project from the Git repository on GitHub, using the following URL to clone the repository:

<a href="https://github.com/robertcasanova99/gatorraider">https://github.com/robertcasanova99/gatorraider</a>

<h1>Game Mechanics</h1>
In this game, the attacker is attempting to cover as much of the terrain as possible, while the defenders attempt to limit the terrain covered by the attacker. The play occurs in two distinct modes: Normal and Vulnerable.

&nbsp;

<h2>Normal Mode</h2>
In Normal Mode, the attacker tries to cover terrain while avoiding the defenders. If any defender reaches the attacker, the attacker dies and loses a life, starting at the initial location once again.

&nbsp;

<h2>Vulnerable Mode</h2>
If the attacker reaches a power pill, the mode changes for a limited time to Vulnerable Mode. In Vulnerable Mode, if the attacker reaches any defender, the defender will die and its “soul” will return to the lair, where it will regenerate. Each power pill, once consumed, is gone until the level changes.

&nbsp;

<h2>Scoring</h2>
For every new location the attacker reaches, the attacker will score points. In addition, attacker receives a bonus for reaching the power pills and for killing defenders. The goal of defenders is to limit the score of the attacker.

<h1>Project Structure</h1>
This code base makes use of the Model-View-Controller (MVC) software pattern:

&nbsp;

Shows Users the Data&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;Modifies the Data

&nbsp;

In this application, the interfaces in the <strong>game.models</strong> package define the format and arrangement of information about the game state. The game start is displayed to the user via the <strong>GameView</strong> class, which draws the game level and game actors to the screen. The behavior of the actors is determined by implementations of the <strong>AttackerController</strong> and <strong>DefenderController</strong>, whose actions change the how the game plays out.

&nbsp;

<h1>Student Work</h1>
Students will design, implement, and test the attacker controller, and evaluation will include consideration of performance and documentation.

&nbsp;

<h2>AttackerController Interface</h2>
Students must implement the <strong>AttackerController</strong> interface by providing the following methods:

&nbsp;

<em>public</em><em> void</em> <strong>init</strong>(Game game)

This method is called once when the game begins. (For some controllers this method may be empty.)

&nbsp;

<em>public</em><em> int</em> <strong>update</strong>(Game game, long time)

Called to update the agent, given game state game after time milliseconds have passed. This method returns a direction for the attacker which will be used to move the attack in the next game tick.

&nbsp;

<em>public</em><em> void</em> <strong>shutdown</strong>(Game game)

Called once at the end of the game for cleanup. (For some controllers this method may be empty.)

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h2>General Requirements</h2>
The StudentAttackerController submission must meet the following criteria:

&nbsp;

1) The controller must use information from the attacker’s state in making decisions. 2) The <strong><sub>init()</sub></strong> and <strong><sub>shutdown()</sub></strong> methods may be optionally left empty.

3) The attacker’s behavior may not be random.

<h1>Game State</h1>
Following is a summary of the most important classes and methods that are a part of the game state and can be used to determine the next action. NOTE: this is not an exhaustive list; please see source code for full information.

&nbsp;

<h2>Game Interface</h2>
A class implementing the Game interface represents a game state.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPillList</strong>()

Get a list of all available pills in the current level.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPowerPillList</strong>()

Get a list of all available power pills in the current level.

&nbsp;

<em>boolean</em> <strong>checkPill</strong>(Node location)

Returns true if the location in question holds an available pill.

&nbsp;

<em>boolean</em> <strong>checkPowerPill</strong>(Node location)

Returns true if the location in question holds an available power pill.

&nbsp;

<em>Attacker</em> <strong>getAttacker</strong>()

Returns a copy of the attacker’s actor object.

&nbsp;

<em>Defender</em> <strong>getDefender</strong>(int whichDefender)

Returns a copy of the defender’s actor object specified (by number).

&nbsp;

<em>List&lt;</em><em>Defender</em><em>&gt;</em> <strong>getDefenders</strong>()

Retrieves a list of a copy of each defender’s actor object.

&nbsp;

<em>Game</em> <strong>copy</strong>()

Return a deep copy of this game state object.

&nbsp;

<em>Maze</em> <strong>getCurMaze</strong>()

Returns a copy of the current maze information

&nbsp;

<em>class</em> <strong>Direction</strong> { public static final int <strong>UP</strong>, <strong>RIGHT</strong>, <strong>DOWN</strong>, <strong>LEFT</strong>, <strong>EMPTY</strong> }

Class containing constants for directions.

&nbsp;

&nbsp;

<h2>Node Interface</h2>
A class implementing the Node interface represents a location in the terrain. It has coordinates and neighbors.

&nbsp;

<em>int</em> <strong>getX</strong>()

Returns the x-coordinate of this location.

&nbsp;

<em>int</em> <strong>getY</strong>()

Returns the y-coordinate of this location.

&nbsp;

<em>boolean</em> <strong>isPill</strong>()

Returns true if this location has or had a pill.

&nbsp;

<em>boolean</em> <strong>isPowerPill</strong>()

Returns true if this location has or had a power pill.

<em>boolean</em> <strong>isJunction</strong>()

Returns true if this location is a fork (has 3 or more neighbors).

&nbsp;

<em>int</em> <strong>getNumNeighbors</strong>()

Returns the number of neighbors this location has.

&nbsp;

<em>Node</em> <strong>getNeighbor</strong>(int direction)

Returns the node neighboring this location in the direction specified.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getNeighbors</strong>()

Returns the nodes neighboring this location as a List.

&nbsp;

<em>int</em> <strong>getPathDistance</strong>(Node destination)

Returns the distance of the shortest path between this location and the destination.

&nbsp;

&nbsp;

<h2>Maze Interface</h2>
A Maze object, representing the terrain, has the following methods:

&nbsp;

<em>Node</em> <strong>getInitialAttackerPosition</strong>()

Returns the starting location of the attacker.

&nbsp;

<em>Node</em> <strong>getInitialDefendersPosition</strong>()

Returns the starting location of the defenders.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPillNodes</strong>()

Returns a list of the Node objects where pills are.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPowerPillNodes</strong>()

Returns a list of the Node objects where power pills are.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getJunctionNodes</strong>()

Returns a list of the Node objects that are forks (have 3 or more neighbors).

&nbsp;

<strong>&nbsp;</strong>

<h2>Actor Interface</h2>
The Actor interface defines methods that are common to all characters (attackers and defenders alike).

&nbsp;

<em>Node</em> <strong>getLocation</strong>()

Returns the current location of the actor.

&nbsp;

<em>int</em> <strong>getDirection</strong>()

Returns the direction that the actor is currently facing.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPathTo</strong>(Node destination)

Returns a list of nodes defining a path between the current location and the destination.

&nbsp;

<em>int</em> <strong>getNextDir</strong>(Node target, boolean approach)

Returns the next direction the actor should move it to approach (if <sub>approach</sub> is true) or flee (if false) the target.

&nbsp;

<em>int</em> <strong>getReverse</strong>()

Return the direction that is the reverse of where the agent is currently facing.

&nbsp;

<em>Node</em> <strong>getTargetNode</strong>(List&lt;Node&gt; targets, boolean nearest)

Given a list of targets, find the closest (if <sub>nearest</sub> is true) or furthest (if false) from the actor.

&nbsp;

<em>Actor</em> <strong>getTargetActor</strong>(List&lt;Actor&gt; targets, boolean nearest)

Given a list of actors, find the closest (if <sub>nearest</sub> is true) or furthest (if false) from the actor.

&nbsp;

<em>Void</em> <strong>addPathTo</strong>(Game game, Color color, Node node)

Adds a visual path of the user’s choice of color from the actor to a specific node. An example of its usage is provided in the default StudentAttackerController file.

&nbsp;

&nbsp;

<h2>Attacker Interface</h2>
An Attacker object, representing the attacker’s actor, provides the following methods:

&nbsp;

<em>List&lt;</em><em>Integer</em><em>&gt;</em> <strong>getPossibleDirs</strong>(boolean canReverse)

Returns a list of potential directions that the agent could move in. If <sub>canReverse</sub> is true, this can include the direction opposite the one the agent is currently facing.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPossibleLocations</strong>(boolean canReverse)

Returns a list of potential locations that the agent could move to from its current location. If <sub>canReverse</sub> is true, this can include the location in the direction opposite the one the agent is currently facing. The list will always be of size 4, but if the attacker cannot move somewhere the direction’s index in the list

(<em>list.get(direction)</em>) will be null.

&nbsp;

&nbsp;

<h2>Defender Interface</h2>
A Defender object, representing a defender’s actor, provides the following methods:

&nbsp;

<em>boolean</em> <strong>isVulnerable</strong>()

Returns true if the defender is in a vulnerable state.

&nbsp;

<em>boolean</em> <strong>requiresAction</strong>()

Returns true if the actor currently requires an action to properly continue functioning (due to junction, etc.)

&nbsp;

<em>int</em> <strong>getVulnerableTime</strong>()

Returns the amount of time left that the actor will be vulnerable.

&nbsp;

<em>int</em> <strong>getLairTime</strong>()

Returns the amount of time remaining that the actor will spend in the lair.

&nbsp;

<em>List&lt;</em><em>Integer</em><em>&gt;</em> <strong>getPossibleDirs</strong>()

Returns a list of potential directions that the agent could move in, excluding the direction opposite the one the actor is currently facing.

&nbsp;

<em>List&lt;</em><em>Node</em><em>&gt;</em> <strong>getPossibleLocations</strong>()

Returns a list of potential locations that the agent could move to from its current location, excluding the location in the direction opposite the one the agent is currently facing.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>Configurations</h1>
In the top right corner (if you are using Intelli-J) you can find a drop-down of all the configurations which appear as such:

&nbsp;

&nbsp;

&nbsp;

<u>Example – Visual:</u> Visual gameplay of the example implementation of StudentAttackerController .

<u>Human – Visual:</u> Visual gameplay that can be controlled with arrow keys.

<u>TestAgent – Visual:</u> Visual gameplay of your StudentAttackerController.

<u>Example – Scored:</u> Example of the scoring process for the example implementation.

<strong><u>TestAgent – Scored:</u></strong> This is what will be used to grade your submission.

<u>Example – Debug:</u> Runs 5 example trials and saves data about each game state to exec/experiment.txt.

<u>TestAgent – Debug:</u> Runs 5 of your trials and saves data about each game state to exec/experiment.txt.

&nbsp;

In order to see a specific trial (0-indexed), you must edit the configuration for the TestAgent – Scored, and add the trial number at the end of the program arguments. For example, if I want to see the 55<sup>th</sup> trial, it would appear as such:

&nbsp;

&nbsp;

Hit Ok, and then run the TestAgent – Scored. The trial will be visually shown once it arrives at that trial.

<h1>Deliverables</h1>
Students will provide the following deliverables upon completion of the project:

&nbsp;

<ul>
<li>java file (as defined in the specification above)</li>
<li>Design and Post-Mortem document including identification of the following:
<ol>
<li>Diagram(s) and description of attacker behavior and methods with description (100-300 words)</li>
<li>Identifications of successes (“what went right”) and failures (“what went wrong”) (~300 words)</li>
<li>Reflection on project (one per student; 100-300 words)</li>
</ol>
</li>
</ul>
<h1>Grading</h1>
Grading of the project will be as follows:

&nbsp;

<strong>Design &amp; Post-Mortem Document – 30% </strong>

This section of the grade will be based on completion and quality of the design and post-mortem document.

<strong>&nbsp;</strong>

<h2>Agent Performance – 70%</h2>
The remaining portion of the grade will be based on assessment of student agent performance, with a score of 6400 points average over 100 tests attaining 100% credit:

&nbsp;

<table width="264">
<tbody>
<tr>
<td width="114">Pct of Example</td>
<td width="60">Grade</td>
<td width="90">Example</td>
</tr>
<tr>
<td width="114">110%</td>
<td width="60">100%</td>
<td width="90">7,040</td>
</tr>
<tr>
<td width="114">75%</td>
<td width="60">75%</td>
<td width="90">4,800</td>
</tr>
<tr>
<td width="114">1%</td>
<td width="60">1%</td>
<td width="90">64</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>&nbsp;</strong><strong><em>&nbsp;</em></strong>

&nbsp;
