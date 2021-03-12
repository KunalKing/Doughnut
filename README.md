# Doughnut

![celluloid-shot0005](https://user-images.githubusercontent.com/50693369/110743799-a31c2700-825e-11eb-9b2b-89a55b095528.jpg)

Hello everyone, this is the famous doughnut code which was first seen in 2006, The code doesn't do that much but it's worth it to build and see its output.
Requirements - C, GCC Compiler.

/*.....How it works....*/

1. At its core, it’s a framebuffer and a Z-buffer, which render pixels. Since it’s just rendering relatively low-resolution ASCII art.
2. All it does is plot pixels along the surface of the torus at fixed-angle increments.
3. The “pixels” it plots are ASCII characters corresponding to the illumination value of the surface at each point: .,-~:;=!*#$@ from dimmest to brightest. No      raytracing required.

/*.....How to run the code.....*/
step 1 - Install the build-essential packages
         In order to compile and execute a C program, you need to have the essential packages installed on your system. Enter the following command as root in your          Linux Terminal.
         
         $ sudo apt-get install build-essential
         
Step 2 - Compile the C program with gcc Compiler
         In your Terminal, enter the following command in order to make an executable version of the program you have written.
         
Syntax: $ gcc [programName].c -o programName
        $ gcc  Doughnut.c -o Doughnut
        
Make sure your program is located in your Home folder. Otherwise, you will need to specify appropriate paths in this command.

step 3 - Run the program
         The final step is to run the compiled C program. 
Syntax: $ ./programName
        $ ./Doughnut
