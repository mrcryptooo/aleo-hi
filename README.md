discord handle : @mrcryptoo
# HelloWorld in leo 😍

![enter image description here](https://miro.medium.com/v2/resize:fit:828/format:webp/1*ooKP0GZpCIpFzUPqR8u43w.png)

Unexpectedly for everyone (even for me) after part 5 of the Leo tutorials, it’s not part 6, but 0. All because one day my creative genius realized that our tutorial series lacks a starting point where I will explain the introductory moments. Moreover, from reluctance to increase the numbers of all parts by 1, an insight descended on me that you can simply call the first part zero (programmer moment). Thus, I ask you to start understanding leo from this simple project.


# What is Leo

Let’s start with what this language is so good for and why it is needed. Leo is a functional statically typed programming language designed for writing private applications. Leo’s main advantage is that it allows developers, even those with no knowledge of cryptography, to hash incoming information by using a zero-knowledge protocol. The hashing system will allow you to choose which data will become public and which will remain with the user, and the zero-knowledge protocol blocks information leakage.

In general, the language for the lazy, just great. Outwardly, Leo resembles JavaScript, so for those who have had experience programming in JS, it will be easy to master Leo as well.

Now let’s move on to installing the working software. Aleo has developed its own compiler for Leo. You can download it from the following link, choosing your OS: [https://aleo.studio/](https://aleo.studio/). Or you can use the online application: [https://play.leo-lang.org/](https://play.leo-lang.org/).

So, we have installed the working environment, now we create a new project. This can be done in two ways. The first is to simply click on “create new project” in the center of the screen. The second way is using the terminal. However, Leo must be installed before you can start working with the terminal. I have already explained the installation process in article 5. If you are much more comfortable working with the terminal than with graphics, then I advise you to read article 5 and return here. To create a new project using the command line, use the following command (leo new command, then the name):

![enter image description here](https://imageupload.io/ib/lScDrZmrj9NGGEY_1699103988.png)

Next, we create a project and the following picture opens before us:

![enter image description here](https://imageupload.io/ib/WT7uDGGtz5VH7lW_1699104091.webp)

At first glance, everything looks complicated and incomprehensible, but I assure you, it is not. The arrow after main indicates the return data type of the function, a and b are variables, they are in a separate file with the name of your project and the extension .in along with registers, where they are already defined and assigned values. The register contains the value returned by the main function:

![enter image description here](https://imageupload.io/ib/cx2xMvc1xEHoPhU_1699104263.webp)

At the top you can also see a green arrow, by clicking on which we will launch our program. You can start the program in several ways:
![enter image description here](https://imageupload.io/ib/0eD7snqivlGVSHp_1699104379.webp)

Build — syntax checking and compiling our program  
Setup — generating a proving key and creating an outputs/helloworld.lpk file as well as a verifying key and creating an outputs/helloworld.lvk file  
Prove — using input from /inputs/helloworld.in file, generates proof and creates outputs/helloworld.proof file and proof key in outputs/helloworld.lpk file  
Run — directly launching the program, checking the proof and saving it to the outputs/helloworld.proof file using the outputs/helloworld.lvk verification key, and finally outputting and saving the results.

After the program runs, a file is created. outputs/hello-leo.out , where the output values ​​returned by the main function will be located.

That’s all. Today we have installed working software for programming on Leo and learned about the structure of the program.
