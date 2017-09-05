inputfile= computing
1. `sicasm` generates prog.lst and prog.obj ... outputs bugs. (compiles?)
2. <pre>sicsim

	R
	loader
prompt: DEVF1
	prog.obj
</pre>
<b>no other objects so hit enter till the end.</b>

3. <pre> A
	S
	b 115			after figuring out the break point
	R   			untill breakpoint reached. 
</pre><pre>   	
     d r
     	d 100-1ff
     	Q
</pre>
