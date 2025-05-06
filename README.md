# cse318-offline-assignment-3-probabilistic-model-solved
**TO GET THIS SOLUTION VISIT:** [CSE318 Offline Assignment 3-Probabilistic Model Solved](https://www.ankitcodinghub.com/product/cse318-offline-assignment-3-probabilistic-model-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96940&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE318 Offline Assignment 3-Probabilistic Model Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Offline on Probabilistic Model

Once upon a time there lived a baby ghost named Casper. He was very adorable, playful and surprisingly friendly towards humans. One day he was flying over a city when he noticed a group of small children playing hide and seek in an abandoned warehouse. He too wanted to play with them. But when he was descending he broke a tree branch that scared off the children. Feeling disheartened he started roaming in the warehouse. He went to one room from another and saw stockpiles of different goods creating obstacles in his movement. To make things worse, he got lost in one such room. He was roaming around in the room but could not find a way out. Feeling afraid, he started crying. Now, you thought of helping him by escorting outside. But you need to locate him since he is invisible to humans. You went to the room where Casper got lost, with a ghost sensor. The details of the sensor is described later. Your job is to find Casper and help him get his way back.

Environment Description

Assume the room is an n X m grid with k obstacles. You should take n, m, k and the positions of k obstacles as input. Initially, every empty cell (i.e., without any obstacle) of the grid is equally likely for Casper to be in. He can move to any adjacent cell (that shares an edge or a corner) or stay in the same cell at any particular time unit. But it is more likely that he moves to a cell that shares an edge with previous cell (e.g. say this cumulative probability is P=0.9) and moving to any of these options is equally likely. The same is true for the remaining cells for a cumulative probability of 1-P. Note that, you may have to calculate the exact values probability of moving from one cell to another based on the obstacles in the adjacent cells.

Ghost Sensor Specification

The ghost sensor is a sophisticated device. When it is placed in a grid cell, it can detect if Casper is in the same cell or in any adjacent cell (sharing an edge or corner) by blinking a red light (although it cannot pinpoint his location). However, the sensor may sometimes show false reading, but you can assume its reading is mostly correct (say 85% times on average). At each time step, you can only take sensor reading at exactly one grid cell. Please note, presence of obstacles does not impact the ghost sensing capability of the sensor.

Task

You have to model the aforementioned problem using HMM. At each time step, you should show the probability of Casper being in a cell for every grid cell both before and after you detect his presence in a cell with the sensor. Please check this demonstration for more clarification.

Input/Output Format

The first line will contain 3 integers, n, m and k (3 ≤ n, m ≤ 20, 0 ≤ k ≤ n*m). Each of the next k lines will contain two space separated integers, u, v (0 &lt; u &lt; n and 0 &lt; v &lt; m) indicating position of obstacles. The following lines each denotes either sensor reading at a particular cell or enquire about the most likely location of Casper. Sensor reading is identified by the

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
command R u v b (b = 0 or 1) and the enquiry of Casper’s location is identified by the command C. Your program should terminate when Q is given as input.

After reading the grid dimensions and obstacles (first k+1 lines), print the initial probability of Casper being in a grid cell, for all the cells. After each R command, print the updated probability of Casper being in each cell. After each C command, print the most probable position of Casper. After the Q command, bid farewell to Casper.

Sample Format

The following sample is given so that you understand the input-output format better. It does not resemble the correct output based on the given input.

</div>
</div>
<div class="layoutArea">
<div class="column">
(0,0) (1,0) (2,0) (3,0) (4,0) (5,0)

</div>
<div class="column">
O O O O

</div>
<div class="column">
OO O

(5,6) (5,7) (5,8)

</div>
</div>
<div class="layoutArea">
<div class="column">
(5,0) Sample Input

</div>
<div class="column">
(5,1)

Dummy Output

</div>
<div class="column">
(5,3)

</div>
<div class="column">
O (5,4)

</div>
<div class="column">
(5,5)

</div>
<div class="column">
(5,9)

</div>
</div>
<div class="layoutArea">
<div class="column">
(5,2)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6 10 8 10 11 12 21 26 27 37 54 R301 R520 C R501 Q

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Initial Probability:
[A 6 X 10 grid where each cell without obstacle has
a probability value = 1/52, not necessarily in the
fraction form, it can be real number instead. Eacg
cell with obstacle has a probability value = 0.]
</pre>
<pre>Probability Update (1st Reading):
[The probabilities of the cells around (3,0) will
increase while those of others may decrease.]
</pre>
<pre>Probability Update (2nd Reading):
[The probabilities of the cells around (5,2) will
decrease while those of others may increase.]
</pre>
<pre>[Casper is most probably at (4,0) [assuming it has
the highest probability value among the cells]]
</pre>
<pre>Probability Update (3rd Reading):
[The probabilities of the cells around (5,0) will
increase while those of others may decrease.]
</pre>
Bye Casper!

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
