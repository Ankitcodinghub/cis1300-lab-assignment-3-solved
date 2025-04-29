# cis1300-lab-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CIS1300 Lab Assignment 3 Solved](https://www.ankitcodinghub.com/product/cis1300-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115312&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS1300 Lab Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Lab Assignment 3 – Preparing for Git and Learning from the Midterm

Instructions

1. In your Debian 10 VM or from your laptop, open a Terminal and secure shell into the linux.socs.uoguelph.ca server:

$ ssh &lt;username&gt;@linux.socs.uoguelph.ca

where you replace &lt;username&gt; with your UoG login username. On the linux.socs server, create the following directory tree (if it does not exist already):

~/CIS1300 Remember that ~ refers to your home directory

~/CIS1300/Assignments

~/CIS1300/Assignments/Assignment1

~/CIS1300/Assignments/Assignment2

~/CIS1300/Assignments/Assignment3

~/CIS1300/Assignments/Assignment4

~/CIS1300/Labs

~/CIS1300/Labs/Lab1

~/CIS1300/Labs/Lab2

~/CIS1300/Labs/Lab3

~/CIS1300/Labs/Lab4

2. Go back to your Debian VM (you can do this by typing logout or exit). Transfer all your code for Assignment 1 from your Debian VM to the linux.socs server using secure copy. For example, if you are in your Debian VM Assignment 1 directory:

$ scp *.c &lt;username&gt;@linux.socs.uoguelph.ca:~/Assignment1

*.c means to transfer all files whose filenames end in .c. Copy all source code, test files, header files, Makefiles, etc.

Transfer all your code (as much as you have done so far) for Assignment 2 from your Debian VM to the linux.socs server using secure copy.

Copy any code that you have for Lab Assignments 1 and 2.

3. Return to the linux.socs server:

$ ssh &lt;username&gt;@linux.socs.uoguelph.ca

Go to the directory ~/CIS1300/Labs/Lab3.

In this directory create a C source code file called countLeaps.c. This program will do the following tasks:

a. Read in 2 command line parameters: startYear numLeaps where startYear is a number representing a year and numLeaps is an integer number.

b. The program will first check that it has the right number of parameters and if yes it will assign them to variables of appropriate type and name.

c. You will then create a while loop (and it MUST be a while loop) that checks if a year is a leap year starting from the startYear, and then incrementing startYear by one, and stopping when it has found numLeaps number of leap years.

d. When the program finds a leap year it will print it out on its own line. For example,

$ ./countLeaps 2000 3

would output

2000

2004

2008

The routine that finds if a year is a leap year will be a function that you write called isLeap(). Its declaration is:

int isLeap ( int year );

It returns 1 if the year is a leap year and 0 if it is not.

You will be compiling and linking in the following way:

$ gcc -ansi -Wall -c isLeap.c

$ gcc -ansi -Wall -c countLeaps.c

$ gcc -ansi -Wall countLeaps.o isLeap.o -o countLeaps

Put these compilation rules into a Makefile so that if you run:

$ make countLeaps

you will get the executable countLeaps. Also add the following to your Makefile:

clean:

rm countLeaps countLeaps.o isLeap.o

Grading

• CIS1300 directory structure on linux.socs.uoguelph.ca = 1

• Working countLeaps program = 1

• Working Makefile = 1
