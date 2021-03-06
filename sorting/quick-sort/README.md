Quick Sort Technic 
-------------------
Quick Sort is a divide and conquer algorithm , Quicksort first divides a large list into two smaller sub-lists: the low elements and the high elements,Quicksort can then recursively sort the sub-list.
<br/>
<img src="http://upload.wikimedia.org/wikipedia/commons/9/9c/Quicksort-example.gif"/>

Algorithm
---------
<ol>
   <li> Pick an element called a <i>Pivot</i> from array </li>
   <li> Reorder of array so that elements with less values than pivot place to left pivot, and elements with higher values than pivot place right after pivot </li>
   <li> Recursively less array and higher array
   <li> return as merge less values, pivot , and higher values to one array </li>
</ol>

Usage
-----
<pre>
$data = array(5,23,3,5,8,1,0,3,8,9,11,15);
print_r(vquicksort($data));

//result after sorting
Array
(
    [0] => 0
    [1] => 1
    [2] => 3
    [3] => 3
    [4] => 5
    [5] => 5
    [6] => 8
    [7] => 8
    [8] => 9
    [9] => 11
    [10] => 15
    [11] => 23
)
</pre>

Tested
------
<ol>
<li> result numbers on array is good</li> 
<li> result with number,character . number will be place on first before character </li>
<li> result character on array is good </li>
<li> other , i hope any someone can tested with more complex data, and if have bugs please create issue and i will try to fix that </li>
</ol>

Reference
---------
about [Quick-Sort](en.wikipedia.org/wiki/Quicksort) <br/>
about [Sort on Programming] (http://www.squidoo.com/sorting-algorithms)<br/>
video [Quick-Sort-video](www.youtube.com/watch?v=ywWBy6J5gz8&feature=relmfu)<br/>
video [Quick-Sort vs Buble Sort](http://youtube.com/watch?v=KMZ_N1PsF4U)<br/>

