yellowco.github.io
==================

A static blog using the Nikola engine. ([handbook](http://getnikola.com/handbook.html))

As per the handbook, to install --

```
sudo pip install nikola
sudo apt-get install libxml2-dev libxslt1-dev python-dev
...
git checkout source
```

To edit configuration file --
```
vi /path/to/root/conf.py
```

To add a new post --
```
cd /path/to/root/
nikola new_post -t "post_title"
```

To deploy --
```
cd /path/to/root/
nikola github_deploy
```

To create a theme, see the [manual](http://getnikola.com/creating-a-theme.html).
