# week1 exercise observations

1. **Command:** `mkdir -p $HOME/portfolio/week1 ; cd $HOME/portfolio/week1`  
   **Expectation:**  what I expected is for it to create a portfolio for week 1
   **Outcome:** what occured the command made a directory structure within the users home and then it alternates to the '' cd HOME/portfolio/week1′′whichbecomesthenewdirectory.soitbecomes /portfolio/week1HOME/portfolio/week1'' which becomes the new directory. so it becomes ~/portfolio/week1HOME/portfolio/week1′′whichbecomesthenewdirectory.soitbecomes /portfolio/week1. 
2. **Command:** `cd ~`  
   **Expectation:** I anticpate that this command  will save the week 1 portfolio  
   **Outcome:** the truth was that it altered the present directory --> becoming users home directory. it removed the highlighted "~/portfolio/week1$" from script hiding it. 

3. **Command:** $ rm -r portfolio 
   **Expectation:** this command will certainly delete the portfolio that was created
   **Outcome:** the command "rm -r" was utilised to clear the portfolio

4. **Command:** mkdir -p $HOME/portfolio/week1 & cd $HOME/portfolio/week1  
   **Expectation:** my assumption is that it would create a similar out put like from part 1 where it would make /portfolio/week1   
   **Outcome:** the reaction was that no such file or directory is found 

5. **Command:** $ cd ~   
   **Expectation:** I expect this to save the $HOME/portfolio/week1  
   **Outcome:** the reply given was Done mkdir -p $HOME/portfolio/week 1, command altered it ---> users home directory 

6. **Command:** $ rm -r portfolio   
   **Expectation:** learning from previous experince i believe this will execute where it will clear the directory once again 
   **Outcome:**  it looks like the execution of the command was to to clear the portfolio

7. **Command:** $ mkdir -p $HOME/portfolio/week1 && cd $HOME/portfolio/week1  
   **Expectation:** I think this command will form a directory similiarly to the previous source codes written from 1. 
   **Outcome:** the outcome was "~/portfolio/week1$"  which looks like it generated directory structure within users home directory   

8. **Command:** $ echo "Hello World"   
   **Expectation:** I assume this will print hello world  
   **Outcome:** the command proved to execute "Hello World"  

9.   **Command:** $ echo Hello, World   
     **Expectation:** I forsee the same fate as the previous command in #8  
     **Outcome:** the command outlined "Hello, World" so a comma was the differnce from previous #8.  

10. **Command:** $ echo Hello, world; Foo bar  
     **Expectation:** I intercept the command will do the following: print hello world and foo bar 
     **Outcome:** the result became "Hello, World" and then stating 'Foo' not found  

11.  **Command:** $ echo Hello, world!   
      **Expectation:** I apprehend that it will print Hello,World! again here learning from previous execution Echo has shown us to print the hello world script.  
     **Outcome:** The conclusion: it printed the line "Hello, World!"


12. **Command:** `$ echo "line one";echo "line two"`  
   **Expectation:** I await that the line 1 and 2 prints.  
   **Outcome:** The consequence of the order resulted in 'line one' & 'line two' to be printed by separating the both for making new lines.

13. **Command:** `$ echo "Hello, world > readme"`  
   **Expectation:** I figure this will just print Hello, World.  
   **Outcome:** The follow up of this order became "Hello, World > readme".

14. **Command:** `$ echo "Hello, world" > readme`  
   **Expectation:** I predict that it will print a line of Hello world > readme.  
   **Outcome:** End result was Hello world transferred to a saved file readme within directory.

15. **Command:** `$ cat readme`  
   **Expectation:** I foretell that it could show all the classification.  
   **Outcome:** The command issued "Hello, World".

16. **Command:** `$ example="Hello, World"`  
   **Expectation:** I Imagine this will print Hello World.  
   **Outcome:** The answer it gave was "=Hello, World".

17. **Command:** `$ echo $example`  
   **Expectation:** I recon it will print example.  
   **Outcome:** It printed a new line with no context just empty space.

18. **Command:** `$ echo ’$example’`  
   **Expectation:** I doubt that this will print a line of "example" due to the fact that i have learnt now that echo will mostly print the output.  
   **Outcome:** The effect from the bash order was "$example".

19. **Command:** `$ echo "$example"`  
   **Expectation:** I trust that this command will print the line consisting of "$example".  
   **Outcome:** The bash order validated a new line only without any added characters.

20. **Command:** `$ echo "Please enter your name."; read example`  
   **Expectation:** I speculate that this is going to prompt me to enter a name.  
   **Outcome:** The command appeared "Please enter your name," which then accepted a given name.

21. **Command:** $ echo "Hello $example"  
   **Expectation:** I think that it will print "Hello $example".  
   **Outcome:** The outcome from the bash command was "Hello Zain" due to the fact that, that was the given name from previous bash code #20.

22. **Command:** $ three=1+1+1;echo $three  
   **Expectation:** I guess this will calculate the integers to become 3.  
   **Outcome:** The command only printed the "1+1+1".

23. **Command:** $ bc
   **Expectation:** I expected it to be a calendar.  
   **Outcome:** I ended up figuring that this was a calculator which can be used to work out 1+1+1 which then proves '3' (I used the hint 'quit' to exit out from the calculator to proceed).

24. **Command:** $ echo 1+1+1 | bc 
   **Expectation:** I should anticipate this to workout the following bash order due to the fact that bc is used in this command along with the echo 1+1+1.  
   **Outcome:** The end result was that it printed 3 which clarified that it worked out 1+1+1 = 3.

25. **Command:** $ let three=1+1+1;echo $three  
   **Expectation:** I question that this will print out 3 and $three.  
   **Outcome:** The command gave an output of the integer 3 proving that it is a form of calculation.

26. **Command:** $ echo date  
   **Expectation:** From the teachings of recent bash commands I can predict that this command will display "date".  
   **Outcome:** The order issued a new line of "date".

27. **Command:** $ cal  
   **Expectation:** I think that this is a short term for calculator which will be enforced.  
   **Outcome:** Turns out to be a calendar showing today's date such as month/year/the number of days of the month October (31
28. **Command:** `$ which cal`  
   **Expectation:** I reckon that this will display all calendar months.  
   **Outcome:** The command showcases "/usr/bin/cal" which I think directs where the cal can be found or where to be found.

29. **Command:** `$ /bin/cal`  
   **Expectation:** I project that the bash will create a path to cal.  
   **Outcome:** The command was presenting the month/year/the date/the week Mon-Sun.

30. **Command:** `$ $(which cal)`  
   **Expectation:** I envision that it will unveil years.  
   **Outcome:** The bash command disclosed the month/year/the date/the week Mon-Sun.

31. **Command:** `$ ‘which cal‘`  
   **Expectation:** I consider that it will portray the same as the previous bash commands which is demonstrating the calendar of the current month accurately.  
   **Outcome:** The creation occurs as "which cal: command not found" which exhibits that quoting was not functional.

32. **Command:** `$ echo "The date is $(date)"`  
   **Expectation:** As I see it, it seems like it will print the date as the command is being straightforward and uses echo as well as the quotation and also the brackets and date to highlight of printing.  
   **Outcome:** The command results in justifying "the date is Thu 5 Oct 00:58:55 BST 2023" so the accuracy of time and date.

33. **Command:** `$ seq 0 9`  
   **Expectation:** I estimate that this will present integers.  
   **Outcome:** The reaction produced numbers ranging in format of a column from 0-9.

34. **Command:** `$ seq 0 9 | wc -l`  
   **Expectation:** I suspect that this will display the numbers from 0-9.  
   **Outcome:** The command uncovered "10" which shows us that it counted from 0,1,2,3,4,5,6,7,8,9 to form the no.10.

35. **Command:** `$ seq 0 9 > sequence`  
   **Expectation:** I deem this to identify the sequence from 0-9.  
   **Outcome:** The bash indicates that '>' transfers the seq 0 - 9 to a file.

36. **Command:** `$ wc -l < sequence`  
   **Expectation:** I presume that this will show us where the file of sequence can be found.  
   **Outcome:** The observation programs '10' which indicates that it counts the sequence from 0-9.

37. **Command:** `$ for I in $(seq 1 9) ; do echo $I ; done`  
   **Expectation:** I anticipate the command to display integers.  
   **Outcome:** The command demos the numbers from 1-9.

38. **Command:** `$ (echo -n 0 ; for I in $(seq 1 9) ; do echo -n +$I ; done ; echo) | bc`  
   **Expectation:** I figure that this will show seq 1-9 in a column type of way.  
   **Outcome:** The assessment of this command came to be '45'. This uses calculator as highlighted by bc at the end and '-n' forbids for a new line, the I within `$(seq 1 9)` creates 'for' loop which emphasizes through numbers created through 'seq 1 9' order, the '|' functions as a pipe.

39. **Command:** `$ echo -e ‘#include <stdio.h>\nint main(void) \n{\n printf(“Hello World\\n”);\n return 0;\n}’ > hello.c`  
   **Expectation:** I reason that this command will have the output "Hello World" and make a new line.  
   **Outcome:** The process of this command "echo" acts as operating structure to print the characters to terminal, '-e' becomes utilized to permit interpretation of backslash escapes within the made echo string. Single quotations acts to enclose the C source code which you want to print. `"#include <stdio.h>\nint main(void) \n{\n printf(“Hello World\\n”);\n return 0;\n}"` this forms a source code file known as hello.c consisting of Hello world.

40. **Command:** $ cat hello.c  
     **Expectation:** I recon that it will print hello world  
     **Outcome:** the outcome was "#include <stdio.h>, int main(void), printf(“Hello World\n”); so the cat command role was to implement the expression of a file. so add that will hello.c it is going to present us the code for hello world from previous command created in #39

41.  **Command:** $ gcc hello.c -o hello  
     **Expectation:** I guess that the hello.c file will transfer to hello  
     **Outcome:** The executed command brings the gcc compiler to bring hello.c source code to compile it and form a program hello in the same directory

42.  **Command:** $ ./hello  
     **Expectation:** My assumption Is it creates a new line of hello world  
     **Outcome:** this command allows the file hello.c which consists of hello world code to print out the following code: Hello World which then demonstrates the c source code to become a working functional code

