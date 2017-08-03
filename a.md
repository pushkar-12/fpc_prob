In Dexter’s laboratory is present a series of 2N input and output nodes located at marked positions in a line. A node is either an input type or an output type, not both. There are exactly N input nodes and N output nodes. There is a control server at one end of the line of nodes that ensures the proper functioning of all nodes.Dexter wants to conduct an experiment in which the most important requirement is that there **must not be** any position x (1≤x≤N), such that the no of output nodes located at positions less than or equal to x (with the position nearest to the control server being considered 1) exceed the no of input nodes located at positions less than or equal to x.

**Unfortunately, his sister Dee-Dee, has randomly arranged the input and output nodes.**
Now to fulfil the condition of the experiment, Dexter has to set the nodes right. To change the configuration of nodes already set by his sister, he can only swap two **adjacent** nodes at a time, but he can perform as many swaps as would be required.

Clearly there is not much time so Dexter would like to minimize the no of such swaps to get to the correct configuration. So given the initial configuration of nodes, help him know the minimum no of swaps required.

**Input:**<br/>
First line of input contains T no of test cases.<br/>
Each line of test case contains a string composed of two characters ‘I’ and ‘O’ denoting an input node and an output node respectively. It will be ensured that there are equal no of ‘I’ nodes and ‘O’ nodes. The node represented by first character of the string will considered to be at position-1 and nearest to the server.

**Output:**<br/>
For each input case, output a single integer that is the answer for that case.<br/>

**Constraints:**<br/>
1≤T≤10<br/>
2≤2N≤100000<br/>

**Sample Input:**<br/>
*5<br/>
OOOOIIII<br/>
OOIIOIOIIO<br/>
IIOOIIOO<br/>
OIOIOI<br/>
OOOIOIOI*<br/>

**Sample Output:**<br/>
*10<br/>
5<br/>
0<br/>
3<br/>
3*<br/>




