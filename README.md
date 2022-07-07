[![Test](https://github.com/kolypto/py-myproject/workflows/Test/badge.svg)](/kolypto/py-myproject/actions)
[![Pythons](https://img.shields.io/badge/python-3.7%E2%80%933.10-blue.svg)](noxfile.py)

Initialize your new repository, if you haven't already:

    $ git init
    $ git commit --allow-empty -m 'Initial'

Add a project template and merge it into master:

    $ git remote add template git@github.com:kolypto/py-_project-template.git
    $ git fetch template
    $ git merge template/master --allow-unrelated-histories

Now change the name of your project:

    $ ./rename-project.sh my-app-name

From now on, pull updates from upstream:

    $ git fetch template
    $ git merge template/master
