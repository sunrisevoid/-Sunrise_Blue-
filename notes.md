# Notes

## Step 1

1. I created a virtual environment for python using venv. This is to isolate the packages so that it would be used exclusively for the project.

2. I then installed flask, it is a way for the server to communicate with web applications.

3. I did "pip freeze" and output it into "requirements.txt", this is to show the required python packages for this particular setup.

4. Looking into "requirements.txt", I found there a few packages installed, one of which is the aforementioned flask. I also recognized Jinja and Werkzeug as they were mentioned in the description of flask. I later discovered that all the others were installed by flask, here is a list of them and what each does:

- blinker: currently I don't fully understand this, I think it's something to do with setting up a way to distribute small amounts of information in specific contexts.
- click: a way to make CLIs in an easy way, includes a bunch of useful stuff for CLI creation.
- Flask: I mentioned this before.
- itsdangerous: a way to send data in a safe way, metaphorically it's a locker with a combination lock on it.
- Jinja: a way to make templates for specific usages, templates as in a combination of static text and dynamic objects and/or variables.
- MarkupSafe: a way to keep text inputs and objects secure and to make sure it doesn't interact with any other code, a safeguard against injection attacks.
- Werkzeug: A library for WSGI stuff, includes a bunch of useful things.
Putting on my thinking cap, I think all of this is to make web interfaces a lot easier and with less headaches, big brain stuff.
