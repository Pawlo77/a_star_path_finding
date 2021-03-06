# a_star_path_finding
Graphical implementation of <b>A* path finding algorithm</b> using python and pygame.<br>
It has random <b>generator of perfect mazes</b>.<br><br>
<img src="example.png" alt="example maze and solution" width="300" height="300" align="middle"/>
<hr>
Options (key map):
<ol>
    <li>
        Standard User Interface - instant response:
        <ul>
            <li><b>Q</b> key to quit</li>
            <li><b>P</b> key to see alg / see alg step by step / hide alg</li>
            <li><b>L</b> key to see maze gen / hide maze generator work</li>
        </ul>
    </li>
    <li>
        Rest - response only in graph creation mode<br>
        (not available during alg work):<br>
        <ul>
            <li><b>O</b> key to use diagonal conections or not</li>
            <li><b>R</b> key to reset alg but keep board</li>
            <li><b>C</b> key to reset entire board </li>
            <li><b>SPACE</b> key to start alg</li>
            <li><b>G</b> key to generate maze</li>
            <li><b>F</b> to loop maze generation and solving with animations</li>
        </ul>
    </li>
</ol>
<hr>
Color map:
<ul>
    <li><b>orange</b> - starting node</li>
    <li><b>purple</b> - end node</li>
    <li><b>black</b> - barriers</li>
    <li><b>green</b> - open nodes (that algorithm considered but didn't checked yet)</li>
    <li><b>red</b> - closed nodes (that algorithm visited directly)</li>
    <li><b>blue</b> - shortest path nodes</li>
</ul>
<hr>
To change graph size:
<ul>
    <li>change intiger value of <b>Settings().ROWS</b> to change graph rows number</li>
    <li>change intiger value of <b>Settings().COLS</b> to change graph columns number</li>
</ul>

To change window size (in pixels):
<ul>
    <li>change intiger value of <b>Settings().WIDTH</b> to change x window dimension</li>
    <li>change intiger value of <b>Settings().HEIGHT</b> to change y widow dimension</li>
</ul>
