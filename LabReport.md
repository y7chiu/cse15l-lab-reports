# How to Remote Access and FileSystem

--------------------------------------

Hi!

This is my CSE15 Lab Report 1! My name is Yi-Chan Chiu, and everyone can call me Frankie!

Today, I am going to teach you how to `Remote Access and FileSystem`!

--------------------------------------
> Step 1 : Find Out Your Specific Account and Change Password

Go to [Link](https://sdacs.ucsd.edu/~icc/index.php) of the specific account, and there are `Username and Student ID` to put. After putting those into the 
blank, click submit! You will see there are specific accounts listed on the screen. See the specific account username for cse15L (It's like cs15lsp23xx) and  click it. The website will appear the link to let the student change the password. Remember to use the 'username' of the **specific** acount. Once you change the password, the website will give the confirm page for changing sucessfully. And your specific account and password are setting up now!

***Go to the link provided above, you will see the website like this (As picture)**

<img width="1374" alt="截圖 2023-04-06 20 16 36" src="https://user-images.githubusercontent.com/130111605/230534336-bc8d0f3a-0da1-405c-97c3-e0e96c8b436f.png">


***See the specific username for this course, for this course, click on the cs15lsp23xx**

<img width="1291" alt="截圖 2023-04-06 20 24 15" src="https://user-images.githubusercontent.com/130111605/230534929-07a4c4da-dfeb-4f82-ab0e-7c7b84d0e7ce.png">


***Click on the Global Password Change Tool to rest the password**

<img width="1274" alt="截圖 2023-04-06 20 27 27" src="https://user-images.githubusercontent.com/130111605/230535109-fe90bbc6-13ea-4872-acb4-b3c28762d7cb.png">


***Follow the instruction the website given to reset the password and make sure the second picture of the username is the specific account of cse15L course!**

<img width="1157" alt="截圖 2023-04-06 20 29 21" src="https://user-images.githubusercontent.com/130111605/230535245-47f4a4ba-d3a7-4087-87da-819b6207db57.png">
-------------------------------------------------------------------------------------------------------------------------------------------
<img width="1161" alt="截圖 2023-04-06 20 30 13" src="https://user-images.githubusercontent.com/130111605/230535293-76b14a2b-b735-43fc-9705-4375ce57f090.png">

Once the password changed successfully, there are the comfirmation page that tells you account setting finished!

--------------------------------------

> Step 2 : Install Visual Studio Code 

Go to visual studio website [visual studio website](https://code.visualstudio.com/download) to install the vscode. Select the version of your computer operating system (Mac, Windows, or Linux) and follow the further installing instructions. Once you installed, click on the visual studio, and you will see the screen as below. That's mean you installed successfully!


<img width="1429" alt="截圖 2023-04-07 19 12 20" src="https://user-images.githubusercontent.com/130111605/230698809-d931cfc2-0314-4b15-bb71-2c2efbcd62c2.png">

--------------------------------------

> Step 3 : Remotely Connecting

After installing Visual Studio Code, we are going to use terminal to login i the remotely connecting. Open the new terminal in the visual studio code (There is the place called "Terminal", and there is `New Terminal` to click), and student can start login the remotely connecting by using their specific course account (If student have the trouble to login by using the specific course account, please use the original username (the username in front of your UCSD email) and password to login). After loging into the account, the command will opt appear this kind of message. `Are you sure you want to continue connecting (yes/no/[fingerprint])?`. Click yes, and it will log into the **`ieng6`** account successfully! As below:

***Open new terminal and type `ssh username + @ieng6.ucsd.edu` and `password` to login in**
<img width="855" alt="截圖 2023-04-07 19 56 26" src="https://user-images.githubusercontent.com/130111605/230700315-14bdfe6a-2c5b-4854-9731-1915af962a3c.png">


***You will see the screen as this after logining the remotely connecting successfully**
<img width="868" alt="截圖 2023-04-07 19 56 38" src="https://user-images.githubusercontent.com/130111605/230700407-5257629a-9be5-40bc-bbc6-9c3820126000.png">

--------------------------------------

> Step 4 : Trying Some Commands
When you see there is the similar command like `[y7chiu@ieng6-201]:~:12$`, try to operate some commands (Type behind the `$` symbol). There are some commands and features you can try, such as `cd`, `ls`, or `cp`. Please try some of the commands and see how they work!

***Here are some commands you can try**
```
- cd ~
- cd
- ls -lat
- ls -a
- ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the abc is one of the other group members’ username
- cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
- cat /home/linux/ieng6/cs15lsp23/public/hello.txt
```

***The result will look like below's pictures: **
