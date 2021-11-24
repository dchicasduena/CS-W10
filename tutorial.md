
# Github and Git Basic Tutorial

## CS W10 David Chicas

**What is Git?**
> Git is a software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

**What is Github?**
> Github is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management functionality of Git.

To get started you need to change the operating system of your computer to Linux. All Labnet computers are capable of doing this, you just need to restart the machine and select Linux.

To get started with git and Github you will create a Github account. After creating an account you will create a new repository by clicking on the green button in the **Repositories** tab.

![Create Repo](/images/createrepo.png)

After creating your repository you will click on **Code** and copy the url.
This will alow us to connect our repository with our files in the computer.

![Create Repo](/images/copyurl.png)

After copying the url you will create a new folder. Then right-click on the folder and select the option **Open Terminal at Folder**.

After that you will use the following command `git clone https://github.com/username/repo.git` where you can paste your url after the command **git clone**

Then you can use the command `cd CS-W10` to access your new folder. It should look like this.

![Clone Repo](/images/clonerepo.png)

You will then look for the application **Visual Studio Code**, where we will write a simple Python program. Open a new file by doing the following.

![New File](/images/newfile.png)

Once the new file is open you can copy the following code. You need to change `your_name` to your name. Remember to keep the " " or it wont work.

``` py
# This is the program you will be saving in your repository. 
# It is a simple program that will print some information

name = "your_name" # change this to your name, but do not forget the " "

print("\nHello! my name is " + name + ". \nI am learning how to use git!\n")
```

Save the file by clicking on **File** and then on **Save as...** you should save this file as `hello.py` to save your Python file. Now that you have your code ready you can go back to the terminal window and run the following commands In the following order:

- `python hello.py` This will run the code you copied. Checked that the output corresponds to the one in the picture below.

- `git add hello.py` This will add your file to your repository.

- `git commit -m "my first commit` This is a commit. This is a snapshot of your repository, you can add a comment between the " ".

- `git push` This will push the file to your repository.

![Add Commit Push](/images/addcommitpush.png)

Now that you have pushed your code into the repository, you can go back to Github and look at your repository. You should see your file `hello.py` in your repository with the comment of your commit next to it.

It should look like the following picture.

![Show Repo](/images/showcode.png)

If you click on your `hello.py` file you should be able to see your code like in the following picture.

![Show Code](/images/showcode2.png)

Now you know how to add a file to a Github repository and the basics of git! There is a lot more to learn about git and Github, and if you are interested you can check this [tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) out!
