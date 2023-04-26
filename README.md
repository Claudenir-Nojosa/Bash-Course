![Bash](/images/header.jpg)

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Claudenir-Nojosa/Bash-Course.svg?style=social&label=Star&maxAge=2592000)](https://github.com/Claudenir-Nojosa/Bash-Course/stargazers/)

</div>

# 🌌 Fact: Learn Bash the Easiest Way Possible (Even Your Grandma Would Learn) 🌌

## 👣 Step-by-step

<p>
<strong>	1.</strong> Understand what Bash/Shell is <br>
<strong>	2.</strong> Why is it important to learn <br>
<strong>	3.</strong> Shell types <br> 
<strong>	4.</strong> Commands and shortcuts <br>
<strong>	5.</strong> Final considerations

<table>
  <tr>
    <td>   
        <img height="150em" src="/images/t1.png"/>
    </td>
    <td>     
        <img height="150em" src="/images/t2.png"/>
    </td>
        <td>     
        <img height="150em" src="/images/t3.jpg"/>
    </td>
     <td>      
        <img height="150em" src="/images/t4.jpg"/>
    </td>
    <td>      
        <img height="150em" src="/images/t5.jpg"/>
    </td>
  </tr>
</table>
</p>

---
<p align="center">
<img height="250em" src="/images/children.jpg"/>
</p>
<h2> 🎃 What is Bash/Shell (EVEN A CHILD CAN UNDERSTAND) 🎃 
</h2>

<p>
Bash is an acronym for “Bourne Again Shell”, developed in 1989. It is a shell program that runs on a command line interface and has as its main function to control operating systems.

But before talking about what Bash is, we need to talk about the Shell, which is nothing more than a program that controls operating systems, it is as if it were the communication bridge between the core of the Operating System and the user/applications.

This core of the Operating System is called Kernel, it manages the operations of the computer and hardware.

Finally, Shell works in two ways:
<ul>
<li> Through a <strong>GUI (Graphical User Interface)</strong> 
</li>
<li>
Or through an <strong>CLI (Command Line Interface)</strong>
</li>
</ul>

An example of GUI Shells is, in Windows 10, the possibility for the user to control the device's operating system by clicking on taskbar buttons and menus.

However, Bash is a Shells CLI, so for it to work, the user needs to write commands.

🍊 Basic analogy to understand what Shell is 🍊

<p align="center">
<img height="250em" src="/images/orange.jpg"/>
</p>

<p>
Imagine an orange<br>
This orange has the peel part (Shell), which is the layer that bridges the gap between us (user) and the inside (Kernel).
</p>

<h3>Differences between Shell and Kernel</h3>
<ul>
<li>
Shell: Allows the user to communicate with the kernel <br>
Kernel: Controls all system tasks
</li>
<li>
Shell: It is the interface between the kernel and the user. <br>
Kernel: It is the core of the operating system
</li>
<li>
Shell: Execute commands on a group of files  <br>
Kernel: Perform memory management
</li>
<li>
Shell: It is the external layer of the Operating System <br>
Kernel: It is the internal layer of the Operating System
</li>
<li>
Shell: Interacts with the user interpreting machine language <br>
Kernel: Interacts directly with the hardware
</li>

</p>

---

<h2> 🔮 Why is it important to know about 🔮 </h2>

<p>
Learning Bash will allow you to control the operating system like a programmer should. But it's not just a skill for programmers, it can be used by anyone working with <i>data</i>.

<ul>
<li>
Bash is popular, and it pays well. 💵
<p> According to "2020's Stack Overflow's Developer Survey", Bash/Shell is the sixth most used language worldwide, ahead of Python and R. It was also associated with higher salaries, according to the survey.
</p>
</li>
<li>
Command lines help with repetitive data processing 💾
<p> Part of a data scientist's job is to constantly make sure certain information is available, often on a daily basis. Most <i>data</i> is acquired, processed and made available in the same way.
The command line serves this purpose very well as the commands are easily automated and replicated.
</p>
</li>
<li>
Working with text files is easier ⌨
<p>Text files are one of the most common ways to store <i>data</i> files.
</p>
</li>
<li>
Uses less machine resources 🖥
<p> When you are working with a computer with limited resources, and simply want to increase the processing speed, using command lines will always be better than using a GUI, as the GUI will dedicate more resources to render the graphic look.
This works both locally and remotely. When connected remotely, GUI's consume much more resources than CLI's.
</p>
</li>
<li>
You can probably type faster than you can click 🖱
<p> Even if you find that you're faster by clicking, there's a good chance that at least some tasks, you'll be more efficient via the command line.
</p>
</li>
<li>
You can wake yourself up by setting an alarm. 🕰
<p> 

```
sleep 20m && madplay song.mp3
```

</p>
</li>

---

<h2> 🛰 Shell types 🛰 </h2>
<div align="center">
<table>
    <thead>
        <tr>
            <th>
            Linux
            </th>
            <th>
            Windows
            </th>
            <th>
            UNIX
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
            Bourne-Again
            </td>
            <td>
            Aston 
            </td>
            <td>
            Korn  
            </td>
        </tr>
        <tr>
            <td>
            Tcsh 
            </td>
            <td>
            Window Blinds
            </td>
            <td>
            The C 
            </td>
        </tr>
        <tr>
            <td>
            ---
            </td>
            <td>
            Xoblite 
            </td>
            <td>
            Bourne-Again 
            </td>
        </tr>
    </tbody>
</table>
</div>
</p>

---

<h2> 🛸 Commands and shortcuts 🛸 </h2>

<p>
Within Bash there are several commands and shortcuts to speed up procedures, some of them are:

| Commands | Actions |
| -------- | --------- |
| pwd | Print working directory, shows which directory you are currently |
| cd + name of directory | Changes for the respective directory |
| cd ~ | Go back to the root directory |
| cd .. | Go back to the parent directory |
| ls | List files in current directory |
| mkdir + name of the folder | Make directory, creates a new folder |
| touch + name of the file | Creates a new file |
| node + name of the file | Runs the .js archive |
| cls | Clear the command screen |
| start + name of the file | Runs the file |
| rm + name of the file | Removes the file |
| rm * | Removes all the files of a directory |
| rm -r + name of the folder | Removes a folder in a directory |
| CTRL + A | Moves the cursor to the start of the row |
| CTRL + E | Moves the cursor to the end of the row |
| CTRL + L | Clear the command screen (same as <i>clear</i>) |
| TAB | Completes the command we are writing, if there are possibilities to complete |

</p>

---

#####  Of all the shells available, Bash is one of the most popular, user-friendly and manages to surpass previous shells in many ways. Compliant with the POSIX P1003.2/ISO 9945.2 standard, it allows configuring software, extracting system data, manipulating files, automating code compilation processes, monitoring routines, among other functions. Bash documentation is available at the[official site](https://www.gnu.org/software/bash/manual/).