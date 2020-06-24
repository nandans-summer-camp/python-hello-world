# Hello World in Python

The goal of this exercise is to set up your computing environment and practice the workflow we will be using in our pre-course programming material. You will set up a Unix environment with git, Python, a text editor, and pytest, as well as practice using git in the Github Classroom workflow.

### Instructions

1. Setup a Unix environment to work in! Unix means, in effect, either Mac or Linux. If you already use a Mac, it's fine to just stick with it. If you use Windows, you should install a Linux distribution (either in a separate partition or, if you're ready to take a big bold step towards a brighter future, just delete Windows altogether). I recommend [Manjaro](https://manjaro.org/) or [Ubuntu](https://ubuntu.com/). Ubuntu is a bit more popular and the internet is full of guides, which is nice for first-time Linux users, but Manjaro has a great package manager which makes life very pleasant. Any Linux distribution will do, so feel free to read a bit and choose one that you think you will like.

2. Learn to use the terminal (also called console) on your system. Both MacOS and any Linux distribution will come with a terminal, in Mac and Ubuntu (Gnome) this is called "Terminal", in KDE Linux distros it is "Konsole". These applications are _terminal emulators_ and provide a _command line interface_ to your operating system via a _shell_ program (usually either _bash_ or _zsh_). Don't worry about all those terms, that sentence is there so that you can start to become familiar with them and recognize them.

* [This is a great guide to using the terminal](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview). It's created by Ubuntu, but works perfectly for any Linux user and the first few sections should work for Mac as well.

3. Get to know your package manager. For MacOS, I recommend using [Homebrew](https://brew.sh/). For Linux, you will have a default package manager (pacman, apt, yum, etc.). Read a bit about package management on your operating system. Package managers will let you install/manage applications for your system and allow you to do it all from the terminal, which is very convenient.

4. Using your package manager, install `git` on your system if you don't already have it. To check if you have it, run `git --version` from the terminal. The current version is `2.27.0`, but it's not important to have the latest version right now. If you want a newer version, you can use your package manager to install the latest. It's good practice to keep up with the latest versions of your tools. Here are a couple of reasonable guides for learning what git is and how to use it (note: the only features you will need for now are `clone`, `commit`, and `push`):

* [Hello World using just Github](https://guides.github.com/activities/hello-world/)
* [Introduction to git on the command line](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
* [Official Git Documentation](https://git-scm.com/)

5. "Clone" this repository. Cloning and repositories are both concepts from git, which you can read about in the previous guides. Basically, it means "copy files from a remote server to my local computer". With cloning, in addition to the files themselves, you get the "version history" as well.

6. Right now, what you're reading is actually the `README.md` file of this repository. You're probably reading it online, but now that you've cloned the repository to your local computer, you should have this file there too! Go ahead and try and read it. It's a "markdown" file. You can open it in any program that reads plain text files or by using `cat` from the command line.

7. Install Python3 and on your system. The latest version is `3.8`, which is what you should install, but `3.5+` will work fine for now if you already have it.

* _Background:_ there are two "major" Python versions that circulate around: "2" and "3". In general, you should do all your programming in Python3 now, as Python2 is deprecated. However, there are some old programs that still use Python2 and your operating system might use one of these old programs and might have Python2 installed already. If that is the case, don't overwrite the Python2 installation on your computer, you can have both and use python3 for your programming. Follow instructions for your operating system. For MacOS, I recommend using [Homebrew](https://brew.sh/) for installing a version of Python3 that won't overwrite any OS version. For Linux, you can use your package manager to install Python3.

8. Install a text editor or Python IDE that you can use to write Python code. Here are a few text editor options:

* A safe bet would be [VSCode](https://code.visualstudio.com/), which is supported by Microsoft and an active open source community.
* [Atom](https://atom.io/) is a really nice open source project that's also very easy to use and customize. It was created by the folks at Github, which was recently bought by Microsoft.
* [Emacs](https://www.gnu.org/software/emacs/) has been around forever and will be around forever. It's fully free and open source and does everything. But it has a steep learning curve. [Doom-emacs](https://github.com/hlissner/doom-emacs) is a great batteries-included version that is easy to get started with.

You should then install the appropriate Python plugins/extensions. Try to open this folder in your editor, where you should be able to read this file as well as the python files `exercises.py` and `test_exercises.py`.

9. Install the Python package `pytest` on your machine. If you know about virtual environments (or want to learn on your own), you can install `pytest` in a virtual environment you create for each of the assignments. If not using a virtual environment, you can install the package on your machine by running `python3 -m pip install --user pytest` in your terminal.

10. You should now be able to run the command: `pytest` in your terminal, inside this folder. The `pytest` package has installed this command globally and it is available anywhere from your terminal, however, it's behavior will change based on what folder you are in (in the terminal). When run from inside this folder, the `pytest` program will run all the "tests" in this exercise.

Tests are used a lot in programming to ensure that our code does what we want it do it. We will use tests in all our "learning Python" assignments. The tests will "fail" until you have written code that performs the assignment correctly, at which point it will "pass".

11. Open the `exercises.py` file and complete the assignment. Run `pytest` again to see if you completed the assignment correctly. If the test passes, you're done!

12. To "turn in" the assignment you will need to _commit_ your changes and _push_ them to your Github repository.
