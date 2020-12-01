## Fork this repository 🚀

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.


## Clone the repository 🏁

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```bash
git clone https://github.com/SkillshipFoundationIndia/Resources.git
```

## Create a branch ⚓

Change to the repository directory on your computer (if you are not already there):

```bash
cd (filename)
```

Now create a branch using the `git checkout` command:

```bash
git checkout -b your-new-branch-name
```

For example:

```bash
git checkout -b name
```

## Make necessary changes and commit those changes

Do the necessary changes.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add .
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "(Add your message)"
```

replacing `<Add your message here>` with your message.


## Push changes to GitHub 🪂

Push your changes using the command `git push`:

```bash
git push origin <branch-name>
```

replacing `<branch-name>` with the name of the branch you created earlier.


## Submit your changes for review 🚩

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon we will be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
