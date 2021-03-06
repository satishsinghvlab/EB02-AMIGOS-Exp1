## Storyboard (Round 2)

Experiment 1: Write a program to generate 10 KHz square wave using 8051.

### 1. Story Outline:

<p>In this experiment, we give the delay we want and get a corresponding output waveform. If we take initial value as 0 to port 1.0 then the waveform starts with a high status and vice versa since the first command we have taken complements the contents of port 1.0.</p>
<p>The waveform remains high or low as long as the delay program runs and once the delay program is finished it comes to the next line which causes it to jump to the very first statement.</p>


### 2. Story:

We have provided the user with a set of instructions or code which get highlighted while being executed and the corresponding output can be seen on the screen. It helps in enhancing the user’s understanding of the microcontroller and it’s working.

#### 2.1 Set the Visual Stage Description:
When the user land on the simulator page, he can see a window showing the code. Next to it is a window showing the screen for the waveform adjacent to a pin diagram of microcontroller 8051. Above these windows is a window that inputs the value of delay and four buttons:
1. Take initial value as 0
2. Take initial value as 1
3. Clear
4. Start

#### 2.2 Set User Objectives & Goals:
The objective of this experiment is to give users a better understanding of microcontroller’s working and how to generate a square wave using it.
The user has to enter the value of delay in the space provided in the simulator. Having entered a value, he has to choose wether he wants the initial value in port 1.0 to be 0 or 1 after which he can press the start button and a waveform will appear on the screen. If the user wants the waveform to vanish, he simply has to press clear.

#### 2.3 Set the Pathway Activities:

The very first step is to enter the value of delay and then choose wether we want the contents of P1.0 to be 0 or 1. Then we click on the start button and obtain a waveform which can be stopped by clicking on the clear button.

##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:

The simulator is designed to provide the user with maximum ease and hence the user will hardly face any problems while performing it. The user just has to be careful while giving the delay of the input, he has to enter only an integral value. The value of the input can be varies hence a variation in the waveform can be easily noticed.

##### 2.5 Allow pitfalls:
The user will not get any output if he enters a non-numerical value. Also he has to choose the status of port 1.0 before pressing the start button.

##### 2.6 Conclusion:
The simulation requires less than a minute to complete and the results are spontaneous. The questions have been provided in other rounds and those questions are the very basics of performing this experiment so if the user can answer those questions then he surely will be able to build upon it.

##### 2.7 Equations/formulas: NA
Only one equation has been used which is a relation between the delay and frequency.
<br><br>
<pre><code>
        Delay = 1/(2 * frequency),<br>
        i.e., delay is half times the inverse of frequency. <br>
        So, frequency= 1/(2 * Delay)
</code></pre>


### 3. Flowchart 4

![Flowchart](images/flowchart.png?raw=true "Flow Chart")

### 4. Mindmap:
![Mindmap](images/MINDMAP.png?raw=true "Mindmap")

### 5. Storyboard :
![Storyboard](images/FINALIMAGE.png?raw=true "Story Board")
