# streaming-01-getting-started

## Hello there! My name is Levi and this is the first repo for my masters level course in streaming data. 

> Get started with Python for streaming analytics

We assume no prior programming experience and that you want to 
get productive as quickly as possible.

This project uses only content from the Python Standard Library. 
No project virtual environment is required. 

These are popular industry tools - we'll practice with them a lot. 
Getting good at them helps you build better analytics projects more efficiently. 

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured with user.name and user.email - the same email you use for GitHub)

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check!

---

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started.

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured.

- If MacOS - default terminal used

Important: 

- MacOS used 'python3'
- Type each command rather than copy & paste for best results. 
- Wait for each command to complete before running the next command.

```shell
git --version
git config user.name
git config user.email
python --version
python -m pip install --upgrade pip wheel
```

✔️ Make sure all commands complete successfully. 
If not, post your screenshots and the text of the error message in the discussion.
They all must run successfully before continuing.

## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

Important: 

-MacOS using 'python3' 

```shell
python util_about.py
```

✔️ Make sure your script runs successfully. 
If not, post your screenshots and the text of the error message in the discussion.
This script must run successfully before continuing. 
---


## Explore & Execute Project Scripts

With our project repository folder open in VS Code, and having confirmed that we can execute a Python script successfully, it's time to explore. 

Open, read, and run each project script (each file will have a .py extension) in order.

You don't need to fully understand the code yet. 
Instead, read the code and try to figure out what each file is doing.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

Important: 

- MacOS -- python3 
- Wait for each script to finish. Did you generate a new datafile? What is the name?

```shell
python3 process_batch_A.py
```

```shell
python3 process_batch_B.py
```

```shell
python3 process_batch_C.py
```

```shell
python3 process_streaming_0.py
```

✔️ Make sure your scripts complete successfully. 
If not, post screenshots and the text of any error messages in the discussion.
---


## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub.


## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
