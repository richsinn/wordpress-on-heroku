# NOTE
This is a fork of the awesome [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project, which helps you upload a wordpress application to herkou.  One way to use it is to fork the project and then upload the forked project to your heroku instance.  You can follow the instructions [here](http://mchung.github.com/heroku-buildpack-wordpress/).

The rest of the README below is exactly as how it appears in the
original [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project.

# Wordpress on Heroku

This is where changes to your Wordpress site are made.  Changes committed to this directory will overwrite all the vendor defaults.

Generally, you'll be interested in adding plugins, adding themes, and modifying wordpress.conf.erb.
```
└── config                # Config files
    ├── public            # Public directory
    │   └── wp-content    # Themes & plugins
    │       ├── plugins
    │       └── themes
    └── vendor            # Config files for vendored apps
        ├── nginx
        │   └── conf      # nginx.conf + wordpress.conf.erb
        └── php           # php.ini
            └── etc       # php-fpm.conf
```

For everything you ever wanted to know about running Wordpress on Heroku, check out my [heroku-buildpack-wordpress](http://github.com/mchung/heroku-buildpack-wordpress).
