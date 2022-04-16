# project-documentation
Using this space to document steps I take to set up software to start projects in my git repos

[Github Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

# Setting up a virtual environment - venv
#### Use
    This is used to create an environment where only the python libraries that are needed for this project are installed.  It is an alternative to installing libraries globally and helps to ensure that the proper version is installed based on what is listed in the requirements.txt file for the project that is being worked on.  Python3 comes with venv included 

#### Assumptions
    Commands used is for Mac.  Python 3.7.1 or higher is installed

#### Links
    [Python Docs - venv](https://docs.python.org/3/tutorial/venv.html)
    
#### Steps
    1. Create github repo
    2. Clone github repo to machine
    3. cd to repo location on computer
    4. Create the virtual environment
        ```
        python3 -m venv [environment name without brackets] 
        ```
    5. Activate the virtual environment
        ```
        source [environment name without brackets]/bin/activate
        ```
    6. If we are successful activating the virtual environment than we should see the following in terminal
        ```
        ([environment name without brackets]) $
        ```
    7. When we are finished we can deactivate the virtual environment using the following command in terminal
        ```
        ([environment name without brackets]) $ deactivate
        ```
    8. Terminal should no longer display ([environment name without brackets]) in front of terminal prompt.  All packages in the virtual environment will no longer be available
