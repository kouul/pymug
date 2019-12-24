# pymug
website source of pymug.com - python mauritius user group

NOTE: As noted on fb and linked-in, joining our groups on social media adds you as a member on our website. Joining our groups is about commitment to Python. A personal page is created for you with your skills listed. It shows at the very least the path to learn py.

# Website
https://pymug.github.io/pymug/ or http://www.pymug.com

# Structure
the site's structure is dictated by github pages' specifications and handling rather than good standards.

an index.html in every folder, path or lib, is a brillant idea of github (really). See tutorial section below

# Activating Vitual env (Optional)

**Windows:**

Activate (from pymug/):

```
cd pymug-web/scripts/ & activate & cd ..\..
```

or just type

```
win_vactivate
```

Deactivate:

```
cd pymug-web/scripts/ & deactivate & cd ..\..
```

or just type

```
win_vdeactivate
```

# Installing dependencies (If not using venv)

```
pip install -r requirements.txt
```

# Quick start

```
python build.py all
```

to build all

else choose what section to build from: the modules folder

e.g `python build.py blog`

# Add yourself as a member

open an issue with your name,username,date in the format

name / username / date

or open a Pull Request and add your name to the bottom of the file [here](https://github.com/pymug/pymug/blob/master/docs/data/members_basic/members.txt)

# Python version 

3.7

# Tutorial

The website has two folders the `templates/` folder and the output folder, here `docs/`. `data/` folder is used to store data used by `build.py`. 

### Modules development



### API

