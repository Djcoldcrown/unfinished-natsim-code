# Affairs-and-Order

Affairs & order is a nation simulation game, where you can make your own nation, build a military and industry, and declare war.

# Repo installation.

1. Install Git and add Git to PATH. https://stackoverflow.com/questions/26620312/installing-git-in-path-with-github-client-for-windows
2. Type `git clone https://github.com/Djcoldcrown/Affairs-and-Order.git` in the folder you want the repo to be cloned in.

# Flask

1. Install Python (Preferrably 3.8) https://www.python.org/downloads/release/python-380/.
2. Run `pip install -r requirements.txt`, this will install all the modules needed for this repo.
3. Type `flask run` in this repo's folder on your own PC.
4. Navigate to `http://127.0.0.1:5000/` or the url flask gave you in your browser. The website should run

# Celery

# we currently don't use celery so no need to install it

1. Install redis from here https://github.com/microsoftarchive/redis
2. Navigate to the installation path and run `redis-server`
3. Run celery in another terminal window using `celery -A app.celery worker -l info -P gevent`
4. Run Flask in yet another terminal window

Does not work on `repl.it` use `CS50 IDE` or run it on your own machine.
If you are using `CS50 IDE` use `flask run --host=0.0.0.0 --port=8080` instead of `flask run` and add `https://`  at the front and a `/` at the end of the link.
