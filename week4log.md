# week4 exercise observations
--------------------------------------------------------------------------------------------------------
1. **Command:** `$ cd portfolio`  
   **Expectation:** I expect this to make changes to the portfolio.  
   **Outcome:** what occurs from the committed command is that it forms (~/portfolio$) so it makes modification to the running directory which is the portfolio directory.

2. **Command:** `$ git switch master`  
   **Expectation:** I assume this will it will go to master branch.  
   **Outcome:** It changes the active branch to 'master' within git repository through using 'git switch'. The 'master' branch then emerges to be the current active branch.

3. **Command:** `$ mkdir -p week4/framework`  
   **Expectation:** what I expected is for it to form week4 and within it framework.  
   **Outcome:** this command formed a directory structure to utilise the command. Through involving the '-p', it will form a directory. So in this case, it will form the directory "week4/framework".

4. **Command:** `$ cd week4/framework`  
   **Expectation:** I anticipate that this command will create a directory of week4/framework.  
   **Outcome:** what is expected from this order is that it will alter the existing active directory to "week4/framework".

5. **Command:** `$ git branch framework`  
   **Expectation:** I assume this will create a branch of framework.  
   **Outcome:** It forms a new branch within my git repository known as 'framework' through the git branch order. It does not necessarily shift to that branch, it just forms it.

6. **Command:** `$ git switch framework`  
   **Expectation:** I assume this will change to framework.  
   **Outcome:** The order changes the active branch to being 'framework' within GIT repository forming it to be the active branch, utilising the 'GIT switch' to changes to the newly formed branch.

7. **Command:** `$ nano Makefile`  
   **Outcome:**  through using nano I'm opening a text editor which gives me the power to form a file with the given instructions given I have been commanded to include 
1. 'mkdir $(NAME) ;\'==> forms a directory by utilsing the value within '$(NAME)' variable 
2. ">cd $(NAME) && \" ==> modifies the working directory towards the previous step by utilsing the '$(NAME)' variable. 
3. Inside the project directory, it forms many subdirectories:"bin,doc,src,test,lib & config. this ';' spilts the commands. 
4. "Iecho "*" > bin/.gitignore ;\" ===> It forms .gitignore file within 'bin' directory. 
5. "Iecho "*" > lib/.gitignore" ====> similar to the recent step ^^ however the "lib" directroy makes the gitignore to ignore all within lib directory. 

8. **Command:** `$ cat -vTE Makefile`  
   **Expectation:** I intercept the command to showcase the written nano code.  
   **Outcome:** This command outputs the scripts from the Makefile and in every end of a line it has the sign "$" and it shows the tabs as "^I" this approach can be handful for checking out the file for wehnever it has special characthers and control characthers. "Cat" == Is for showcasing the file. "-v" ===> showcases non-printing characthers. "-T" ==>  showcases the tab characthers like '^I'. "E" ===> shows us the '$' in each end of line.  
9. **Command:** `$ make feature NAME=test_output`  
   **Expectation:** I intercept the command will create an output of NAME.  
   **Outcome:** The command carries out a program known as "make", the program is ordered to carry out a certain step known as "feature", In the moment of the steps the information it gets is "NAME" and it assigns a value to "NAME" which is "test_output".

10. **Command:** `$ ls -al test_output`  
    **Expectation:** I anticipate that this will show a list of directories.  
    **Outcome:** This showcases all the files about "test_output" like size, modification date, and ownership.

11. **Command:** `$ git add Makefile`  
    **Expectation:** I predict It will try and add it to git repository.  
    **Outcome:** The command prepares the "Makefile" for the upcoming commit.

12. **Command:** `$ git commit -m "Setting up Makefile to create feature folders"`  
    **Expectation:** I expect this to commit to create the text file.  
    **Outcome:** Forms a new commit which includes the text explaining the modifications.

13. **Command:** `$ git push`  
    **Expectation:** I project that this will send It to my Git hub.  
    **Outcome:** It will sync my committed modifications to my remote CS gitlab repository.

14. **Command:** `$ cd test_output; cd src`  
    **Expectation:** I reckon that this will touch on the current directories of test_output to make it active.  
    **Outcome:** the code will alter the active directory to 'test_output' afterwards to the  'src'  directort within 'test_output'. 'cd test_output' it alters the active directory TO THE 'test_output' directory. This 'cd' means change directory which becomes utilsed to find the diffrent directories within the file system. ';' This makes it so you can execute many commands in order. 'cd src' When 'test_output' has been the active directory then the 'src' will make it so it changes the directory to 'src' where it will be found within the 'test_output' (test_output/src) 

15. **Command:** Create a file called test_outputs.c with the following contents.    
    **Outcome:** I Used nano test_outputs.c to form a file of the provided c code. It includes header files for file operations, string manipulation, libararies and assertations. the constant values ' COM_SIZ','ARG_SIZ' and 'RES_SIZ' are defined for command arguemnts and results, By utilsing '#define' we can easily change it later on (value) If required so easier navigation comapred to manually changing it on each line of code. ''fn int main(int argc, char *argv[])'' such test program reuqest the existing executable and verifys the outputs to standard output which meets the expected values. it can be requested through: "test_outputs <filename consisting of test definitions> " 
    "int main(int argc, char *argv[])" ==> the common feature for 'main' function within c during command line arguments are anticipated. 'argc' : becomes an intger highlighting the number of command line arguments. 'argv[]' becomes an array of strings highlighting the command line arguments. 'arg[0]' becomes the programs label, 'arg[1]' becomes the 1 argument. 

File pointer: 'FILE *fp; = proclaims the file pointer known as 'fp' where it will give entry towards the file descriptor of the pipe, So the pointer will be able to read the output of executed commands. 

'FILE *tests; announces that a diffrent file pointer known as 'tests' will be utilsed to open and read the file conisting  of test definitions. 

Characther arrays like these:  "char command[COM_SIZ];
 char arguments[ARG_SIZ];
 char expected[RES_SIZ];
 char actual[RES_SIZ];
 char command_line[COM_SIZ + ARG_SIZ];" will be declaring many diffrent types of arrays such as 'char command[COM_SIZ];' will be a characther array known as 'command' of size. so each one of those arrays will be holding diffrent values such as: arguments for commands, command names, expected outputs of commands, declaring a characther array known as 'command_line' whose size is ging to match the sum of 'COM_SIZ' & 'ARG_SIZ' it will carry the command string as well as involving the command name as well as arguments for implementation. These declared file pointers, characther arrays shows that the program will include file operations and string manipulations. 

 "tests=fopen(argv[1], "rt");" ==> This just actions so that it can unlock the file known as 'argv[1]'. 
 'argv[1]'==> highlights the intial command line argument read by the c program. within C 'argv[0]' consists of the program name. 
 'rt' shows that the file can be unlocked for reading. 
 "if (tests==NULL)" ==> verifys weather the file was acessed or not. 
"(fgets(command, COM_SIZ, tests)" captures the source code (command) to implement. 

"fgets(arguments, ARG_SIZ, tests)" captures the argument. 
"fgets(expected, RES_SIZ, tests)" reads the anticipated result during when the command becomes tested. this loop carries on tills it has captured all commands from the file, to get correct outcomes. Its important that it obeys the three line format for every test; if not it will not work. 

"strtok(command, "\n");" utilsing 'strtok' takes out new line characthers it does it by taking out from the end of the 'command' string. 
"snprintf" constructs the 'command' & 'arguments' into 'command_line' string. 
"popen" trying to carry out 'command_line', reading the output. 
During the course that 'popen' dont work out ('NULL') there will eb an expected error reply. 

"fp = popen(command_line, "r");" the command is trying to carry out 'command_line' and unlocks the 'pipe' to read the output. 

"if (fp == NULL)
    printf("Failed to run command\n");
    exit(1);" provided there is an error staging the command then the program will output an error text and then it will exit. 

"char message[RES_SIZ + RES_SIZ + 21];" It provides a 'message' array to reserve the feedback regarding weather the commands output becomes identical to the anticpated output. 

"while(fgets(actual, sizeof(actual), fp) != NULL) {" This setting captures the commands output  word for word into the 'actaul' array. 

"snprintf(message, sizeof message, "%s %s %s %s", "Expected ", expected, " and got ", actual);
printf("%s", message);" This forms a feedback text indicating the expected vs the acquired. 

"if(!strcmp(actual, expected)) 
    printf("OK\n");

else 
    printf("FAILED\n");" This verifys weather the 'actual' output correlates to the 'expected' output. In the case it does correspond then it will print "OK" if not then it will be "FAILED"  

" pclose(fp); " computing the outputs, the program will close the 'pipe' 

"fclose(tests);" this will close file consisting of the test definitions. 

"return 0;" the main function ends through gving back '0' showing that there is an execution

this source code runs a command, captures the output and then verifys weather the output corresponds to the expected outcome. A response Is given for ever test, which gives me information if i passed or not with Ok or FAILED. 

16. **Command:** `$ gcc -Wall -pedantic test_outputs.c -o test_outputs`  
    **Expectation:** I expect this to be compiled.  
    **Outcome:** This will compile the C source code within 'test_outputs.c' utilsing the GCC compiler. 

'-wall': tells warnings for usual problems. 
'-pedantic': Imposes firm C standards compliance. 
'-o test_outputs': puts the name of the compiled output to the 'test_outputs' 
after I should get 'test_outputs' if not then I should expect errors. 
17. **Command:** `$ ./test_outputs file_does_not_exist`  
    **Expectation:** I anticipate that this will show an error message.  
    **Outcome:** "./test_outputs" carries out the 'test_outputs' and then the "file_does_not_exist" the filename which is supposed to be executed. The command proves to show an error.

18. **Command:** `$ ./test_outputs`  
    **Expectation:** I predict that this will just show me the test_outputs file.  
    **Outcome:** This will execute the 'test_outputs' and gives a prompt showcasing an error text.

19. **Command:** Create a file called op_test with the following contents.  
    **Outcome:** I Used nano  op_test to form a file of the provided c code. the file illustartes 3 test cases for 'test_outputs'. 'wc -1' this will pass into file 'test_outputs.c' and it shows the output which is '108 test_outputs.c' and so it repeats doing that for the three of them with diffrent outputs  and it will diffrentiate with the actual output to the expected output within the list and then expect a response from the program. 

20. **Command:** `$ ./test_outputs op_test`  
    **Expectation:** I expect that this will run the op_test file.  
    **Outcome:** what occurs within the code is that it will be running the 'test_outputs' file utlisng the 'op_test' file which will act as the input. The program is going to execute tests and diffrentiate actaul outcomes with the anticipated outputs within 'op_test' 

21. **Command:** `$ git add test_outputs.c`  
    **Expectation:** I reckon this will prepare test_outputs.c to be moved.  
    **Outcome:** This renders the 'test_outputs.c' file for the upcoming git commit.

22. **Command:** `$ git add op_test`  
    **Expectation:** I reckon this will prepare op_test to be moved.  
    **Outcome:** Similarly produces all alterations such as new files towards the upcoming Git commit.

23. **Command:** `$ git commit -m "test framework and sample test suite"`  
    **Expectation:** This I assume will be making a commit in Git.  
    **Outcome:** This forms a brand new commit with additional alterations from the staged files and so this commit is going to have text: "test framework and sample test suite".

24. **Command:** `$ git push`  
    **Expectation:** Git Push is going to Sync the files to Git.  
    **Outcome:** The command syncs the commits to the remote Git repository, having the effect of transferring the data there.
--------------------------------------------------------------------------------------------------------
