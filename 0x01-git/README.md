My second readme for the first git task
Updated my readme

Task 0 - 

Step 1: says to create a github account

Step 2: says to create a personal access token : To create a personal access token, you can follow [this tutorial](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) or you can just follow these simple steps:

When logged in to your github account, the next thing to do is:

Access Token Settings:

Click on your profile picture in the top-right corner of the GitHub interface.
From the dropdown menu, select "Settings."

Generate a New Token:

In the left sidebar, click on "Developer settings." (scroll down to the bottom of the github interface)
Click on "Personal access tokens."

Now, you should see two types of tokens: the fine - grained and the classic tokens. As an ALX student, I do not think it was specified on which token we should create, however it is preferable to generate a classic token. 

Break: Let us tell the difference between the fine grained and classic tokens, just a brief explanation
I just believe that fine grained tokens have more security advantage over classic tokens. Unlike fine grained tokens, there would be no need to keep typing passwords as a means for validation. However, it is advisable to use fine grained tokens for more serious tasks.


Next: I generated a classic token, and to do that, you can click on the option "tokens (classic)", it will take you to a new page where you can generate the token.

After that, click on generate new token, make sure to choose the classic token for this task. You might be asked to sign in again just to confirm access.

Now, in the note box, you have to type the token is for, what you prefer, but also make it make sense. You could type in something like "for authorization"

Next is to set an expiration for the token. It is advisable to set it as "no expiration' cause this is mostly the token you will be using throughout your tasks as an ALX student, but you can also do as you wish. After that, the next thing to do is to select scopes, and they have already been specified in the project, all you have to do is go back and check.

If you check, you will see that you are to selct just three options and they are: repo, admin repo hook, and delete repo. It is important to do this step

Then, click on generate token.

Make sure to copy your generated token in a safe place, like your email drafts, notepad or sticky notes on your computer. The token will only be displayed once, so it is safer and advisable to do this

Step 2: Update your profile on the Intranet with your github username.

Step 3: says to create a new repository and how do we do this? ![image](https://github.com/getacupoftea/alx-pre_course/assets/125554239/17e3264e-f584-4dc2-90ad-9716118762ae)

- Click on the "+" icon in the top right corner and select "New repository."
- The next thing to do is fill in the necessary repository details:
Enter a unique name for your repository, in my case, I followed the instructions on my tasks. The name of this repository should be: alx-pre_course
Add a brief description. In my case, the description was given as : I'm now a ALX Student, this is my first repository as a full-stack engineer
Choose between making it public or private, it is based on preferences. However, in my own case as an ALX student, it should be a public repo.
Add a README.md file if needed, although, the instruction says to not add one (I am saying this as an ALX SE student)
- Configure Repository Settings:
Choose a license (if applicable).
Add a .gitignore file (optional). Though, all these were not required in my case.
- Now, that we are done with these, the next thing is to:
Click the "Create repository" button

YAY! We have now successfully created a new repository.

Step 4: Go back to your intranet, and open/launch your sandbox or webterm, depending on which you are using or prefer.

Step 5: Clone your repository: You could simply do this with just the repository URL, by doing this : git clone + repository URL. 
However, as an ALX student, as stated in the task, I am to do this:
git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git
replace the personal token with the already generated token that is in a secure place
replace your username with your github username.

Well, is it safe to say that I do not really know how necessary this is as at the time of writing this README.md file, but I will find out later. LOL

Step 6: Navigate to the cloned repository using the "cd" command, and create a README.md file. Write the content as specified, and if not, create yours based on your preference.

Next, I updated my git identity as required:
git config --global user.email "you@example.com" (replace the text in "" with my email address)
git config --global user.name "Your Name" (replace the text in "" with my username)

Lastly, I git add, git commit with the command (git commit -m "My first commit" - as the commit message, and git push.




