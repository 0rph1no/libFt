# Libft

<!-- ![libftimage](LibFT.png) -->
<img src="LibFt.png"
     alt="Markdown Monster icon"
     style="width: 100%; height: 500px" />

<h2 style="color:#FFFFFF; letter-spacing: 2px">Purpose: </h2>
<p style="letter-spacing: 1.5px;line-height:2rem;">
Libft(Library fortey two) is the <i style="color: #E9756F">first</i> project in the common core circle, in this project we were assigned the task of recreating/recoding most of Clib functions such as strlen, strcpy, atoi...<br><br>
The whole purpose of this project is to learn the <i style="color: #E9756F"><b>basics</b></i> in C programming as well as <i>string manipulation</i>,<i> file manipulations</i>, <i>streams</i>, <i>memory allocation and management</i>
</p>
<br><br>

<img src="easy.webp"
     alt="Markdown Monster icon"
     style="width: 100%; height: 500px" />

<hr>

<h2 style="color:#FFFFFF; letter-spacing: 2px">Global notes: </h2>
<br>
<h3 style="color:#FFFFFF; letter-spacing: 1px">String manipulation/memory management: </h3>
<p style="letter-spacing: 1.5px;line-height:2rem;">
C is a <i style="color: #E9756F">low-level programming language</i> it deals with the computer hardware directly, which means as a C programmer you need to know what happens in the background of ever action and instruction you wrote in your code.
<br><br>
In a function implementation called "strdup" for ex,  we were introduced to memory allocation and pointer to data located in the heap and what is the difference between stack and heap. I wont get into the details of everything but here is an <a href="https://www.geeksforgeeks.org/stack-vs-heap-memory-allocation/" style="color: #16948A">article</a> i find usefull for further reading.
<br>
In other functions (mem*, ex memcpy...), we discovered in details how the computer stores our variables and data in the memory, how much each variable take in memory and what is/types of typecasting.
</p>
<br><br>
<h3 style="color:#FFFFFF; letter-spacing: 1px">File manipulation/streams: </h3>
<p style="letter-spacing: 1.5px;line-height:2rem;">
File manipulation(open, write, read, close) are a mandatory concepts in which every programmer need to dig deep in and understand the underlying working of how the OS handles these files operations.
<br>
In functions such as ft_putstr_fd,*_fd, we learnt what a file descriptor, inode and inode tables are. We understood what is the meaning of input/output/error streams. As mentioned before this is not a in-details explaination of every concept, but for further reading refer to this <a href="https://en.wikipedia.org/wiki/Standard_streams" style="color: #16948A">article</a>.
</p>
<br><br>
<h2 style="color:#FFFFFF; letter-spacing: 2px">Takeaways and skills acquired:</h2>
<br>


|      Soft Skills      |  Hard Skills |
| :-------------:|------:|
|  Problem-solving | Basics C programming |
|    Perseverance   |   Memory management |
| Online Research |    Strings manipulation |