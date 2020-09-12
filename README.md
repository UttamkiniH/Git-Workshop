# Git-Workshop

Hey Devs :octocat:

This repository was created in order to learn about git and github. Let us follow the :point_right: steps given below 
***
### :point_right: Step 1

Go to this website [Github-Workshop](https://git-workshop.netlify.app/) :cloud: the first thing you see after opening the website is that it contains plenty of cards and each  card has its own name **Card title** So now we are going to change the name of any one of the card from **Card title** to **Your Text**.

### :point_right: Step 2

In the top Right corner of this page you can see the **Fork symbol :fork_and_knife:** click on that and it will create a copy of code :page_facing_up:
to your github Repository :pushpin:

### :point_right: Step 3

While you are in the forked repository of the github page, there you can see the green text-box **Code** click on that and copy the **https** URL and now we will have to clone this repository :closed_book: to our local machine :computer: by this command 

```bash
git clone https://github.com/YOUR_USERNAME/Git-Workshop
```
### :point_right: Step 4

Now lets go the the **Git-Workshop** folder by running this command :pencil2:

```linux
cd Git-Workshop
```

let us create a new **branch** in the name **yourtext**
```bash
git checkout -b yourtext
```
you can give any name to your branch but make sure that you remember the branch name.

### :point_right: Step 5

So, now you are in the **Git-Workshop** directory :file_folder: lets go to the folder **dist** where **index.html** file is present 
```linux
cd dist
```

let us open :open_file_folder: the **index.html** since we are using VS code as editor we will use command **code** 
```bash 
code index.html
```
scroll down the HTML code where you have to  rename :pencil: any one of the **card title** to **your text**

### :point_right: Step 6

After saving :bookmark: your file now we have to **add** and **commit** our file to our local git directory.

To **add** :heavy_plus_sign: our file use command.

```bash
git add index.html
```
To **commit** :paperclip: our file use this command and type suitable comments.

```bash
git commit -m "Yourtext"
```

### :point_right: Step 7

Now we need to push your repository :file_folder: to your remote repository :globe_with_meridians:

```bash
git push -u origin branchname
```
branchname is the name given to your branch in **step 4**

### :point_right: Step 8

Now that you have your code in Remote repository you need to **pull request** so that the user of forked repository can merge  your commit 

Go to your git hub page :globe_with_meridians: of forked repository , there will be **message**:envelope: saying that to create a new pull request **click** on that and type your comment and done :exclamation:

There you go you created your new **pull request** :blue_heart:
