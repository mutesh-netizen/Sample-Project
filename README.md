This project was a simple demonstration of setting up a Python file using Git for version control and pushing it to a GitHub repository. The primary purpose of this project was to illustrate the basic steps involved in creating a new file, initializing a Git repository, making commits, and pushing the project to GitHub.

## Steps Followed

I began by creating and editing a Python file. I opened the editor with the command `vim hello.py` and added the following Python code: `print("Hello, world!")`. After saving and exiting the editor, I configured Git by checking the global Git configuration using `git config --global --list`. If needed, I set the user name and email using `git config --global user.name "Your Name"` and `git config --global user.email "your.email@example.com"`.

Next, I initialized a new Git repository by running `git init`. I added the Python file to the staging area with `git add hello.py`. To ensure the file was staged, I checked the status using `git status`, which confirmed that `hello.py` was staged for commit. I then committed the changes with the message "Initial commit to add hello.py" by using the command `git commit -m "Initial commit to add hello.py"`.

After committing the changes, I added a remote repository by linking the local repository to a remote GitHub repository with the command `git remote add origin https://github.com/mutesh-netizen/Sample-Project.git`. Finally, I pushed the initial commit to GitHub with `git push -u origin master`.

## Verification

To verify the setup, I visited the GitHub repository at [https://github.com/mutesh-netizen/Sample-Project](https://github.com/mutesh-netizen/Sample-Project) and confirmed that `hello.py` was present in the repository.

## Usage

To run the Python script, I used the command `python hello.py`, which outputs "Hello, world!".

## License

This project is licensed under the MIT License. 
