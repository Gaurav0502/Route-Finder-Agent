# Route-Finder-Agent
## Problem Statement
Given is weighted locality routes graph with :
1. Vertices as Checkpoints. 
2. Edges as the routes.
3. Edge Weights as the Travel Time.(Randomly alloted to each edge)
 
Moreover, each route is randomly given a status as follows:
<table>
<tr>
<td>Status</td>
<td>Edge Colour</td>
<td>Delay in Travel Time</td>
</tr>
<tr>
<td>Congestion</td>
<td>Red</td>
<td>4</td>
</tr>
<tr>
<td>Construction Work</td>
<td>Blue</td>
<td>8</td>
</tr>
<tr>
<td>Accident</td>
<td>Orange</td>
<td>6</td>
</tr>
<tr>
<td>No issue</td>
<td>Green</td>
<td>0</td>
</tr>
</table>

Comparative analysis of the outcome of a Goal-based agent and a Utility-based agent based on the condition that Lower Estimated Time of Arrival(ETA) better the route. 
## Agent Programming

<b><ins>Environment:</ins></b> Graph of locality

<ins><b>Agent:</b></ins> The agent will be deployed in the environment and it will use the Depth First Search(DFS) to find all the possible routes. Finally, it will evaluate each path based on the Utility that Lower ETA better the path.
