# How to decompile a program, library, etc.
## Instructions

1. You need a decompiler. I recommend you `ILSpy`, it's easier to find and download. But just in case I going to leave you the link. 
 
  Here: x64.ziphttps://sourceforge.net/projects/ilspy.mirror/files/v9.0-preview1/ILSpy_binaries_9.0.0.7618-preview1-x64.zip/download

2. After downloaded, create a folder with the name `ILSpy` and put all the files in the folder.
3. Now, search for the ILSpy.exe file and run it as administrator.
4. You are going to see a window, that one is the decompiler `ILSpy`.
5. Now we are going to search for our path direction where the .exe (our program) file is . For example in my case is this one: `C:\Users\manue\OneDrive\Escritorio\HelloCSharp.exe`. Since I create it from the Command Prompt(CMD) it won't have a debug file with all its resources. That is in my case. Maybe you are going to use VS 2022.
   - Go to vs 2022, then you need to `Build Solution`.
   - After, you need to find for your .exe file, normaly is in this path `C:\Users\manue\source\repos\c#Fundamentals\FUNDAMENTALSFIRSTEXERCISE\bin\Debug\net8.0`.
   - To more details you can use this video: https://youtu.be/N_fy2pTdMAo?si=YqTzeTtZgVbadBPD
   - And These pages: `https://sourceforge.net/projects/ilspy.mirror/` and `https://github.com/icsharpcode/ILSpy` 
6. Go to the decompiler, then go to file, on the top left corner, click `Open` and find your path where the program (.exe) is.
7. You will see the program, resources, your code and many others details in the decompiler. If you read carefully, you will find out how that program or library works.

In conclusion, there are many decompilers, you can use whichever you want. It is a great and useful tool, it helps you to understand deeper your program, library, etc.
