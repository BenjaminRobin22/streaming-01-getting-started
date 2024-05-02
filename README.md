<<<<<<< HEAD
# streaming-01-getting-started

> Get started with Python for streaming analytics

We assume no prior programming experience and that you want to 
get productive as quickly as possible.

This project uses only content from the Python Standard Library. 
No project virtual environment is required. 

These are popular industry tools - we'll practice with them a lot. 
Getting good at them helps you build better analytics projects more efficiently. 

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher =BR Check Complete 
1. VS Code = BR Check Complete 
1. VS Code Extension: Python = BR Check Complete 
1. Git (configured with user.name and user.email - the same email you use for GitHub) = BR Check Complete 

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check! = BR Noted 

---

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started. = BR Documents/git/Robin_44671_8081/streaming-01-getting-started

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured. = BR Complete 

- If Mac/Linux, the default terminal should work. = BR NA
- If Windows, be sure you're using a PowerShell terminal (rather than cmd). = Check

Important: 

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.
- Type each command rather than copy & paste for best results. 
- Wait for each command to complete before running the next command.

```shell
git --version
git config user.name
git config user.email
python --version
python -m pip install --upgrade pip wheel
```

BR Results 

PS C:\Users\RobinBe> git --version
>> git config user.name
>> git config user.email
>> python --version
>> python -m pip install --upgrade pip wheel
git version 2.44.0.windows.1
Ben Robin
Benjamin.Robin22@gmail.com
Python 3.12.3
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: pip in c:\program files\windowsapps\pythonsoftwarefoundation.python.3.12_3.12.1008.0_x64__qbz5n2kfra8p0\lib\site-packages (24.0)
Requirement already satisfied: wheel in c:\users\robinbe\appdata\local\packages\pythonsoftwarefoundation.python.3.12_qbz5n2kfra8p0\localcache\local-packages\python312\site-packages (0.43.0)

✔️ Make sure all commands complete successfully. 
If not, post your screenshots and the text of the error message in the discussion.
They all must run successfully before continuing.

## Execute Utility Script (Diagnostics) - BR Check

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

Important: 

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.

```shell
python util_about.py
```

✔️ Make sure your script runs successfully. 
If not, post your screenshots and the text of the error message in the discussion.
This script must run successfully before continuing. 

Notes for later !!!! this is the path for my file cd C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started

======================================================================
 Welcome to the NW Python Debugging Information Utility!
 Date and Time: 2024-05-01 at 05:23 PM
 Operating System: nt Windows 10
 System Architecture: 64bit
 Number of CPUs: 32
 Machine Type: AMD64
 Python Version: 3.12.3
 Python Build Date and Compiler: tags/v3.12.3:f6650f9 with Apr  9 2024 14:05:25
 Python Implementation: CPython
 Active pip environment:   None
 Active conda environment: None
 Path to Interpreter:         C:\Users\RobinBe\AppData\Local\Microsoft\WindowsApps\PythonSoftwareFoundation.Python.3.12_qbz5n2kfra8p0\python.exe
 Path to virtual environment: C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.12_3.12.1008.0_x64__qbz5n2kfra8p0
 Current Working Directory:   C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started
 Path to source directory:    C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started
 Path to script file:         C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started\util_about.py
 User's Home Directory:       C:\Users\RobinBe
 Terminal Environment:        Native Terminal
 Terminal Type:               cmd.exe
 Preferred command:           python
 Is python available in PATH:   True
 Is git available in PATH:      True
======================================================================
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

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.
- Wait for each script to finish. Did you generate a new datafile? What is the name?

```shell
python process_batch_A.py
```

```shell
python process_batch_B.py
```

```shell
python process_batch_C.py
```

```shell
python process_streaming_0.py
```

✔️ Make sure your scripts complete successfully. - BR note I moved them over to ipynb files becaue am more conforatable with these. 
If not, post screenshots and the text of any error messages in the discussion.
---

## Update Edit README

Edit this README.md file. It uses Markdown, a simple and easy markup language.

- Keep the prerequisites and task headings. 
- Within the task headings, record only the commands that worked on YOUR machine. 
- Remove unnecessary instructions once you've mastered them.
- Add any additional notes that will help you in the future.

## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub. - Committed updates to git


### Option A: Use VS Code (Easy!)

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
1. Important! Above the Commit button, it will say "Message". 
1. You MUST include a commit message. 
1. In the commit message input box, type "initial results".
1. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 

Verify: Open a browser to your GitHub repo and verify the files have appeared.  - BR Verified 
In addition to the original files, you should have one or more new files and an edited Markdown file. 
If not, return to VS Code and edit/execute files as needed. 
Then commit and push again.

Common Issue: If your computer hangs because you forgot the commit message, 
just enter your message in the top line of the file it shows in the editor.
Then click the checkmark in the upper right to close that file and save your commit message.
"Sync your changes" to push to GitHub. 

### Option B: Use Git Bash or Terminal Commands (Easy as well):

Open a new `Git Bash` or Terminal window. Run the following commands one at a time. - BR this is the method I chose. 
They will first add all the files (add "dot"). 
Then they will commit the changes with a message. 
Finally, they will push the changes up to GitHub.

```
git add .
git commit -m "initial results"
git push origin main
```

Open a browser and view your GitHub repository. 
Verify your new files have been successfully pushed to GitHub. 

✔️ Make sure your git add / commit / push completes successfully. 
If not, post screenshots, error messages, and questions in the discussion.
We've all been there when first learning Git and we can help. 
---

## General Recommendations and Troubleshooting

The following are general recommendations and troubleshooting tips.

### Issue: VS Code - No Source Control Icon

Suggestion: If you're in VS Code, and you don't see the Source Control icon with a blue bubble, right-click on the sidebar icons, and make sure "Source Control" is checked.  

### Issue: VS Code wants to install an extension

If VS Code suggests an extension, it's often good to go ahead and try it. 
Do a search on the extension to learn more. VS Code suggestions are usually helpful. 

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
=======
# streaming-01-getting-started

> Get started with Python for streaming analytics

We assume no prior programming experience and that you want to 
get productive as quickly as possible.

This project uses only content from the Python Standard Library. 
No project virtual environment is required. 

These are popular industry tools - we'll practice with them a lot. 
Getting good at them helps you build better analytics projects more efficiently. 

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher =BR Check Complete 
1. VS Code = BR Check Complete 
1. VS Code Extension: Python = BR Check Complete 
1. Git (configured with user.name and user.email - the same email you use for GitHub) = BR Check Complete 

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check! = BR Noted 

---

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started. = BR Documents/git/Robin_44671_8081/streaming-01-getting-started

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured. = BR Complete 

- If Mac/Linux, the default terminal should work. = BR NA
- If Windows, be sure you're using a PowerShell terminal (rather than cmd). = Check

Important: 

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.
- Type each command rather than copy & paste for best results. 
- Wait for each command to complete before running the next command.

```shell
git --version
git config user.name
git config user.email
python --version
python -m pip install --upgrade pip wheel
```

BR Results 

PS C:\Users\RobinBe> git --version
>> git config user.name
>> git config user.email
>> python --version
>> python -m pip install --upgrade pip wheel
git version 2.44.0.windows.1
Ben Robin
Benjamin.Robin22@gmail.com
Python 3.12.3
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: pip in c:\program files\windowsapps\pythonsoftwarefoundation.python.3.12_3.12.1008.0_x64__qbz5n2kfra8p0\lib\site-packages (24.0)
Requirement already satisfied: wheel in c:\users\robinbe\appdata\local\packages\pythonsoftwarefoundation.python.3.12_qbz5n2kfra8p0\localcache\local-packages\python312\site-packages (0.43.0)

✔️ Make sure all commands complete successfully. 
If not, post your screenshots and the text of the error message in the discussion.
They all must run successfully before continuing.

## Execute Utility Script (Diagnostics) - BR Check

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

Important: 

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.

```shell
python util_about.py
```

✔️ Make sure your script runs successfully. 
If not, post your screenshots and the text of the error message in the discussion.
This script must run successfully before continuing. 

Notes for later !!!! this is the path for my file cd C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started

======================================================================
 Welcome to the NW Python Debugging Information Utility!
 Date and Time: 2024-05-01 at 05:23 PM
 Operating System: nt Windows 10
 System Architecture: 64bit
 Number of CPUs: 32
 Machine Type: AMD64
 Python Version: 3.12.3
 Python Build Date and Compiler: tags/v3.12.3:f6650f9 with Apr  9 2024 14:05:25
 Python Implementation: CPython
 Active pip environment:   None
 Active conda environment: None
 Path to Interpreter:         C:\Users\RobinBe\AppData\Local\Microsoft\WindowsApps\PythonSoftwareFoundation.Python.3.12_qbz5n2kfra8p0\python.exe
 Path to virtual environment: C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.12_3.12.1008.0_x64__qbz5n2kfra8p0
 Current Working Directory:   C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started
 Path to source directory:    C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started
 Path to script file:         C:\Users\RobinBe\Documents\git\Robin_44671_8081\streaming-01-getting-started\util_about.py
 User's Home Directory:       C:\Users\RobinBe
 Terminal Environment:        Native Terminal
 Terminal Type:               cmd.exe
 Preferred command:           python
 Is python available in PATH:   True
 Is git available in PATH:      True
======================================================================
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

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.
- Wait for each script to finish. Did you generate a new datafile? What is the name?

```shell
python process_batch_A.py
```

```shell
python process_batch_B.py
```

```shell
python process_batch_C.py
```

```shell
python process_streaming_0.py
```

✔️ Make sure your scripts complete successfully. - BR note I moved them over to ipynb files becaue am more conforatable with these. 
If not, post screenshots and the text of any error messages in the discussion.
---

## Update Edit README

Edit this README.md file. It uses Markdown, a simple and easy markup language.

- Keep the prerequisites and task headings. 
- Within the task headings, record only the commands that worked on YOUR machine. 
- Remove unnecessary instructions once you've mastered them.
- Add any additional notes that will help you in the future.

## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub. - Committed updates to git


### Option A: Use VS Code (Easy!)

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
1. Important! Above the Commit button, it will say "Message". 
1. You MUST include a commit message. 
1. In the commit message input box, type "initial results".
1. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 

Verify: Open a browser to your GitHub repo and verify the files have appeared.  - BR Verified 
In addition to the original files, you should have one or more new files and an edited Markdown file. 
If not, return to VS Code and edit/execute files as needed. 
Then commit and push again.

Common Issue: If your computer hangs because you forgot the commit message, 
just enter your message in the top line of the file it shows in the editor.
Then click the checkmark in the upper right to close that file and save your commit message.
"Sync your changes" to push to GitHub. 

### Option B: Use Git Bash or Terminal Commands (Easy as well):

Open a new `Git Bash` or Terminal window. Run the following commands one at a time. - BR this is the method I chose. 
They will first add all the files (add "dot"). 
Then they will commit the changes with a message. 
Finally, they will push the changes up to GitHub.

```
git add .
git commit -m "initial results"
git push origin main
```

Open a browser and view your GitHub repository. 
Verify your new files have been successfully pushed to GitHub. 

✔️ Make sure your git add / commit / push completes successfully. 
If not, post screenshots, error messages, and questions in the discussion.
We've all been there when first learning Git and we can help. 
---

## General Recommendations and Troubleshooting

The following are general recommendations and troubleshooting tips.

### Issue: VS Code - No Source Control Icon

Suggestion: If you're in VS Code, and you don't see the Source Control icon with a blue bubble, right-click on the sidebar icons, and make sure "Source Control" is checked.  

### Issue: VS Code wants to install an extension

If VS Code suggests an extension, it's often good to go ahead and try it. 
Do a search on the extension to learn more. VS Code suggestions are usually helpful. 

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
>>>>>>> bb14be9a57bfc7f0018b5cb68932209e8f2b8d9d
