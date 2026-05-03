# Goal
Install the claude code harness and run an Anthropic model from the terminal.
Also, install tools that will enable me for future experimentation.

# Step 1: Basic Setup
1. Open terminal
2. type `pwd` should be something like `/Users/<your_name>`
3. Type in `mkdir Repos` then hit enter key
4. Type in `cd Repos` then hit enter key
5. Type in `mkdir Repos` and you should see something like `/Users/<your_name>/Repos`
6. Type in `mkdir personal`
7. Type in `cd personal`

# Step 2: Install Tools
## 2.1: Install uv
1. Go to uv website and follow instructions for your system (e.g., Mac diff from Windows)
2. This likely involves a `curl` command that you copy paste into your terminal and hit enter

## 2.2: Install claude
1. Go to claude website and sign up for a free trial of claude pro
2. Follow instructions to download (should be similar curl command to install)
3. This likely involves a `curl` command that you copy paste into your terminal and hit enter

## 2.3: Install VS Code
1. Go to VS Code website and install for your machine
2. Open VS Code
3. Enable the "shell" command
4. [optional] Install claude code extension

# Step 3: Your First AI Project
1. Go to terminal and make sure your terminal still shows something like `/Users/<your_name>/Repos/personal` when you type and run `pwd`
2. Type `uv init my-first-ai-project` and run the command (hit enter)
3. Type `cd my-first-ai-project` and run the command
4. Type in `claude` and run it. If this is the first time you have run claude, you will need to authenticate. Follow the instructions and take the default parameters. If asked to "trust this" say yes, claude will run in your project.
5. Type something like this and hit enter in the claude prompt box: `create a python script from scratch that prompts the user for a name and then responds with "Hello <name>!"`

Congratulations! You are ready to experiment with your claude code harness leveraging Anthropic models!
