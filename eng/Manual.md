```
Utilizing Github
```


Github is a service that allows users to upload, share, edit and download code with other users. It allows for a group of individuals to work on a coding project without the interference of one another. 

Some benefits of github include:

- Clear documentation of work done by users.
- Division of labor by allowing users to work on the same project without encroaching on other users’ code.
- Tracking changes in code as it goes through different versions.
- Easy public access that allows anyone to contribute and see.

![Image](https://user-images.githubusercontent.com/98681/53048332-597afc80-3449-11e9-899d-e1897031e70e.png)

```
Downloading from the Repository 
```

The first thing one should do is install Git in order to access the repository.
	*Mac* - git-scm.com/download/mac
	*Windows* - git-scm.com/download/win

One should also already have an account made at https://github.com. Register an email, username and password to get started.

![Image](https://i.imgur.com/fLJ1lQn.png)

On the Mac, access the command prompt through the terminal by searching for the program through the search option on the top right.

![Image1](https://i.imgur.com/BT1KntD.png)

On Windows, access the command prompt by typing run in the search bar and typing in cmd or right clicking on the bottom of the screen on Windows 10 and selecting the command prompt.
You should get a window like this.

![Image1](https://www.howtogeek.com/wp-content/uploads/2017/06/wrb_top-650x300.png)

```
Commands:
```

Opening your computer’s command prompt, you should learn some basic commands that will allow you to access the repository.

l**s(mac)/dir(windows):** Allows you to see the files in the current directory.

**cd:** Stands for change directory, it allows you to go through your files on the command prompt. 
Example: Typing cd Documents in the command line will allow you to go to the documents folder.
(Only works if there is a Documents folder in the folder you are currently on.)

![](images/B.png)

**cd** .. (allows you to go up a directory)
Example: Being in Username/Documents and typing cd .. will make you go back up to the Username folder and out of the Documents folder.

![](images/C.png)

**cd** xxxx (allows you to a certain directory, xxxx stands for directory you wish to go such as documents; username/downloads; desktop)
Example: Typing in cd Username/Documents/Github while in the Username folder will put you straight into the Github folder located in your Documents folder.

![](images/D.png)

**git clone:** Allows you to download the repository and puts it into the directory you are in by its name.

![Image](https://i.imgur.com/a80wiEO.png)

**git status:** Shows us the difference between the file we have and the one in github.

![Image](https://i.imgur.com/JhRTvTI.png)

**git add:** Adds new files or changes to the repository. 

Type git add (file name) to add your desired file and the changes associated with that file.

Type git add .. to add all changes to the repository.
(You must be in the correct directory to add the desired changes)

![Image](https://i.imgur.com/d9OHJfa.png)

**git commit ( -m “message here”):** To commit the file or change to the repository after adding it in.(Does not sync it up with the github yet) -m is input a message for the change.

![Image](https://i.imgur.com/d12iJhS.png)

(Press the esc button and then type :wq to escape the message line if do not put a message after the -m command and wish to escape.)

![Image](https://i.imgur.com/7CV2biE.png)

**git push:** Pushes any changes made on the machine to the github, changing the project on the repository. 

![Image](https://i.imgur.com/2xYpArb.png)

**git pull:** Pulls any changes or files different on the machine from the github.(Only works when in the directory of the repository)
![](images/E.png)

**git:** Shows all the commands available.

![](images/A.png)

	Accessing Altibase’s repository
1. Go to Altibase’s Github at https://github.com/ALTIBASE.

   ![Image](https://i.imgur.com/tQDyvdk.png)

2. To access the desired repository in the website in this case, go to Documents.

   ![Image](https://i.imgur.com/arCk4rB.png)

   

   

3. Clone the url through the green button on the link.

   ![Image](https://i.imgur.com/kbwMBS5.png)

```
Utilizing Altibase’s repository
```

1. Open up the command prompt on your computer.

2. Use command cd(command directory) and cd .. to navigate through the files and find your github folder.
   ![Image](https://i.imgur.com/f5frlWE.png)


   Type in ls to determine the files inside of your directory. 

   The command cd Documents would put you in the Documents folder.

   The command cd .. would put you out of Documents and back to your username folder.

   The github folder will automatically download in the documents folder unless stated otherwise. That is where all your Altibase repositories will go.

3. Use command git clone (copied link) to put the repository in desired folder.
   (This will put a copy of the repository in the folder)

   Type in the command ls to determine the name of the repository.
   ![Image](https://i.imgur.com/a80wiEO.png)

4. Input any desired files and changes through your desired code writing program.

   ``` From here, I will be using a custom repository called test1 as an example```.

5. Use command git status to identify any untracked files in the folder. 

   ![Image](https://i.imgur.com/JhRTvTI.png)

   As shown, Manual.md is shown as the file that is different from the machine's file and the GitHub's file.

6. Use command git add (desired files) or git add ..(to add all changes) to add changes to the repository.

   ![Image](https://i.imgur.com/d9OHJfa.png)

   The box in the red line indicates what happens if you try to add something while you are not in the correct dictionary.

7. Use command git commit (-m “ “ to input any messages) to lock desired changes to the repository.

   ![Image](https://i.imgur.com/d12iJhS.png)

   This command prompt shows what has been changed on the repository.

   ![Image](https://i.imgur.com/7CV2biE.png)

   (Press the esc button and then type :wq to escape the message line if do not put a message after the -m command and wish to escape the message that it prompts you to make)

8. Use command git push to add the desired changes to the Altibase github.
   ![Image](https://i.imgur.com/2xYpArb.png)

```
Using Typora
```

Typora is a simple markdown editor that allows you to edit, read and write text while utilizing github. It allows the user to easily edit text in a format that is compatible with github's text format. 

**Getting started on Typora**

1. Open Typora on your computer. 

   ![](images/F.png)

2. Click file at the top and click open to open your desired file.

   ![](images/G.png)

   The left side should show all the files located in the file with the main screen on the right showing the content of the file you selected.
   ![](images/H.png)

**Importing images on Typora**

1. Go to your github's repository and click on the upload files.

   (You may want a folder to store in all the images)

   ![](images/J.png)

2. Add in the images you want in your repository.

   ![](images/K.png)

3. Pull the images from github to your computer's repository.

   ![](images/E.png)

4. Type in ``![What you want to name the image](Image Location)`` Since it is located in my images folder and called A.png, I type in images/A.png.

   ![](images/L.png)

5. Push the changes you made to your github.

   ![Image](https://i.imgur.com/2xYpArb.png)