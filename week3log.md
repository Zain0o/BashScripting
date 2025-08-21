# week3 exercise observations
--------------------------------------------------------------------------------------------------------
1. **Command:** `$ cd ~`  
   **Expectation:** what I expected is for it to display a list of directories.  
   **Outcome:** the command committed an alternation towards the running directory towards the user's home Directory, the representation of ("~") becomes a home directory.

2. **Command:** `$ cd portfolio`  
   **Expectation:** I expect this to make changes to the portfolio.  
   **Outcome:** what occurs from the committed command is that it forms (~/portfolio$) so it makes modification to the running directory which is the portfolio directory.

3. **Command:** `$ mkdir week3`  
   **Expectation:** I expect this to create a directory.  
   **Outcome:** 'mkdir' becomes utilised to form a new directory known as 'week3' within the local repository.

4. **Command:** `$ mkdir week3/greeting`  
   **Expectation:** I anticipate this will form a greeting directory.  
   **Outcome:** 'mkdir' becomes utilised to form a new directory known as 'greeting' within the week 3 directory.

5. **Command:** `$ cd week3/greeting`  
   **Expectation:** I foresee it changing the directory to week3/greeting.  
   **Outcome:** It alters the recent working directory to becoming 'week3/greeting' directory.

6. **Command:** `$ git branch greeting`  
   **Expectation:** I envision that this will form a branch of greeting.  
   **Outcome:** forms a new Git branch known as 'greeting'.

7. **Command:** `$ git switch greeting`  
   **Expectation:** I imagine this will switch the directory.  
   **Outcome:** transfers to 'greeting' branch, forming it to be the main branch.

8. **Command:** Create a file called greeting.c with the following contents.  
   **Outcome:**  so a file known as 'greeting.c' was formed to display the provided C code within 'week3/greeting' directory. The code showcases a C function which outputs 'hello world!'.  
   

9. **Command:** `$ gcc -Wall -pedantic -c greeting.c -o greeting.o`  
   **Expectation:** I anticipate that this is going to prepare the files.  
   **Outcome:** compiles the 'greeting.c' code file into a file known as 'greeting.o'. It utilises the GCC compiler. It makes the C code ready for upcoming connection as well as forming an executable program.

10. **Command:** Create a file called test_result.c with the following contents.  
   **Outcome:**  I Used nano test_result.c to form a file of the provided C code.  
   

11. **Command:** And create a file called greeting.h with the following contents.  
    **Outcome:**  here I used nano again to get to the text editor and put in the following C code. Ctrl + O to enter the text and Ctrl + X to exit the nano text editor after saved.  
    

12. **Command:** `$ echo greeting.o >> ~/portfolio/.gitignore`  
    **Expectation:** I predict that this will combine the directories.  
    **Outcome:** This joins 'greeting.o' to the '.gitignore' file within my portfolio directory, signaling git that this should be ignored.

13. **Command:** `$ echo libgreet.a >> ~/portfolio/.gitignore`  
    **Expectation:** I presume this will also combine the directories.  
    **Outcome:** It joins up 'libgreet.a' together with .gitignore file signaling that GIT need to ignore that particular library file.

14. **Command:** `$ ar rv libgreet.a greeting.o`  
    **Expectation:** I await that this will create a library.  
    **Outcome:** forms a constant library called 'libgreet.a' and then joins the file greeting.o together through the 'ar' code.

15. **Command:** `$ gcc test_result.c -o test1 -L. -lgreet -I.`  
    **Expectation:** I foresee that this will execute the files.  
    **Outcome:** It puts together the 'test_result.c' code file to an executable program known as test1, so it connects the program with the 'greet' library (-lgreet) which shows the particular library and paths.

16. **Command:** `$ ./test1`  
    **Expectation:** I expect that this will showcase the file.  
    **Outcome:** applies test1 program.

17. **Command:** `$ git add -A`  
    **Expectation:** I expect that this will add to GIT.  
    **Outcome:** produces all alterations such as new files towards the upcoming commit.

18. **Command:** `$ git commit -m “greeting library and greeting test program”`  
    **Expectation:** I predict this will make a commit.  
    **Outcome:** forms a new commit which includes the text explaining the modifications.

19. **Command:** `$ git push`  
    **Expectation:** I project this will sync to GIT.  
    **Outcome:** advances committed modifications through the remote Git repository.

20. **Command:** `$ git switch master`  
    **Expectation:** I foresee this will switch the branch.  
    **Outcome:** It changes the active branch to 'master' within git repository through using 'git switch'. The 'master' branch then emerges to be the current active branch.

21. **Command:** `$ git branch vectors`  
    **Expectation:** I assume this will form a new branch.  
    **Outcome:** It forms a new branch within my git repository known as 'vectors' through the git branch order. It does not necessarily shift to that branch, it just forms it.

22. **Command:** `$ git switch vectors`  
    **Expectation:** I Imagine this will switch to the vector branch.  
    **Outcome:** The order changes the active branch to being 'vectors' within GIT repository forming it to be the active branch, utilising the 'GIT switch' to changes to the newly formed branch.

23. **Command:** `$ cd ~/portfolio/week3`  
    **Expectation:** I imagine this will change directories.  
    **Outcome:** This alters the active directory to "~/portfolio/week3." It switches to the week3 directory inside my portfolio directory.

24. **Command:** `$ mkdir vectors`  
    **Expectation:** I expect this will make a new directory.  
    **Outcome:** Forms a new directory called 'vector' within the week3 directory, so this will become the directory where I am expected to work on my 'vector' project.

25. **Command:** `$ cd vectors`  
    **Expectation:** I anticipate that this will change the directory.  
    **Outcome:** The command changes the recent active directory towards the newly formed 'vector' directory. This gives me control to begin working on my project within this file location.

26. **Command:** Create a file called vector.h with the following contents.  
    **Outcome:** Using Nano I'm forming a file with the given instructions to define a constant 'SIZ' with the int of 3 by declaring a C function 'add_vectors' which takes three int arrays as arguments.  
   

27. **Command:** Create a file called test_vector_add.c with the following contents.  
    **Outcome:**  Through using nano I'm opening a text editor which gives me the power to form a file, with the given instructions given I have been commanded to include C library header <assert.h> & "vector.h" I am also starting to define a C programs Main Function. The xvec & yvec is going to be the inputs to the vector arithmetic routines, zvec is going to take the return value, the goal is also to test every element of the returned vector. Hoping the asserts got processed means there were no faults so we return 0.  
   

28. **Command:** And now create the code to actually “do the math” – vector.c.  
    **Outcome:**  By using nano I'm opening a text editor which gives me the power to form a file, with the given instructions given, I connect every element of x to the correlated element of y, keeping answer in z, it becomes the calling codes duty to make sure they become the correct size and to also make sure they have been declared. Next, I return an error code (0 in this moment proves no error) however is going to add the program logic to manage errors.  
29. **Command:** `$ gcc -Wall -pedantic -c vector.c -o vector.o`  
    **Expectation:** I imagine this will compile the files.  
    **Outcome:** Utilising the GCC compiler, it compiles the vector.c code into the file 'vector.o'. '-Wall' turns on warning context to assist in finding potential errors within the code, '-pedantic' ensures strict compliance with the C language standard, '-c' specifies the particular input file to be compiled, and '-o vector.o' indicates that the output file will be named 'vector.o'.

30. **Command:** `$ ar rv libvector.a vector.o`  
    **Expectation:** I expect this will connect the files and show the library.  
    **Outcome:** The 'ar' command is used to form and update a static library named 'libvector.a', adding the file 'vector.o' to it. The 'ar rv' indicates that the library can be created or amended.

31. **Command:** `$ gcc test_vector_add.c -o test_vector_add1 -L. -lvector -I.`  
    **Expectation:** I envision this will make one of the files executable.  
    **Outcome:** It compiles 'test_vector_add.c' code into an executable program named 'test_vector_add1', linking the program with the 'vector' library.

32. **Command:** `$ ./test_vector_add1`  
    **Expectation:** I predict this will execute 'test_vector_add1'.  
    **Outcome:** Executes the 'test_vector_add1' program, the composed test program for vector addition.

33. **Command:** `$ git add -A`  
    **Expectation:** I expect this will prepare the commit.  
    **Outcome:** Processes all modifications inside the portfolio git repository, making them ready to be committed.

34. **Command:** `$ git commit -m “code to add two vectors of fixed size”`  
    **Expectation:** I think this will create a git commit with text.  
    **Outcome:** Forms a new git commit with informative text, highlighting the alterations that have occurred within the commit, specifically for adding the two vectors of fixed sizes.

35. **Command:** `$ git push`  
    **Expectation:** I predict that this will send the file to gitlab.  
    **Outcome:** The 'git push' command sends the committed changes to the remote Git repository, syncing the changes to the CS gitlab.

36. **Command:** Change the assert(5==zvec[2]); line to be assert(5==zvec[1]); and recompile test to see what happens.  
    **Outcome:**  Altering the line to "assert(5==zvec[1]);" executes as a pass! If it didn't equal 5 in the "zvec[1]", then the assertion would lead to errors, meaning it didn't work out.  
    

37. **Command:** Edit vector.h so it contains this.  
    **Outcome:**  I used nano vector.h to form a file of the provided C code. It's meant to work out the dot product of the two fixed-size vectors, with the defined value of SIZ being 3, representing the size of the vectors. The 'add_vectors' uses addition and keeps the answers to a different set. The 'dot_product' uses multiplication and then adds up the final answers.  
    

38. **Command:** Edit vector.c so it contains this.  
    **Outcome:**  I used nano vector.c to form a file of the provided C code. By summing up the element of x to the related element of y, keeping the answer in 'z'. It's the calling code's duty to ensure the correct size and also that they have been declared. By returning an error code (0 highlighting no error), however, is going to add the program logic to control real errors afterward. "res" acts as a local variable to control the outcome as the working out taking effect.  
    

39. **Command:** And create test_vector_dot_product.c so it contains.  
    **Outcome:**  I used nano test_vector_dot_product.c to form a file of the provided C code. Within the text file, the 'assert.h' is being utilized as a header and macro, as well as having the 'vector.h' header consisting of the declarations of vector functions. 'main' acts as a function and is the initial step of the test program. The two integer arrays 'xvec' & 'yvec' and every 'SIZ' of those arrays become inputs to the 'dot_product' function. It modifies 'xvec' & 'yvec' arrays with a set of values, working out the dot product of 'xvec and 'yvec,' these arrays become arguments, and the outcome will be found in the 'result' variable. The assertion uses the 'assert' macro to verify the outcome of the dot_product can be found within the 'result' variable. If the outcome is the same as the anticipated value 11, then it will pass; if not, then an expected error text is encountered. The main function's return of 0 highlights a functioning executable code.  
    

40. **Command:** `$ gcc -Wall -pedantic -c vector.c -o vector.o`  
    **Expectation:** I predict this will combine the files.  
    **Outcome:** This compiles the vector.c code into the file 'vector.o', utilizing the GCC compiler. The '-c' flag indicates that only compiling is taking place.

41. **Command:** `$ ar rv libvector.a vector.o`  
    **Expectation:** I assume this will connect both files.  
    **Outcome:** The 'ar' command is used to form and update a static library named 'libvector.a', adding the file 'vector.o' to it. The 'ar rv' indicates that the library can be created or amended.

42. **Command:** `$ gcc test_vector_dot_product.c -o test_vector_dot_product1 -L. -lvector -I.`  
    **Expectation:** I imagine this will send 'test_vector_dot_product.c' to 'libvector.a'.  
    **Outcome:** Compiles 'test_vector_dot_product.c' and links it to 'libvector.a'.

43. **Command:** `$ ./test_vector_dot_product1`  
    **Expectation:** I assume this will execute the file.  
    **Outcome:** Verifies the program to see if the 'dot_product' function performs as anticipated.

44. **Command:** `$ git add -A`  
    **Expectation:** I predict this will prepare the commit.  
    **Outcome:** Produces all alterations such as new files towards the upcoming commit.

45. **Command:** `$ git commit -m “code to calculate dot product of two vectors of fixed size”`  
    **Expectation:** I expect this to create a commit involving the text.  
    **Outcome:** Forms a new commit which includes the text explaining the modifications.

46. **Command:** `$ git push`  
    **Expectation:** This I anticipate will push the changes to CS gitlab.  
    **Outcome:** It will sync my committed modifications to my remote CS gitlab repository.
--------------------------------------------------------------------------------------------------------






