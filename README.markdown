**NOTE:** This is a fork of the awesome [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project template, which helps you upload a [Wordpress](http://wordpress.org) application to [Herkou](http://heroku.com). The project template is actually used by the [heroku-buildpack-wordpress](https://github.com/mchung/heroku-buildpack-wordpress) project to successfully configure and deploy a Wordpress application to Heroku. You can follow the instructions of how to make use of this project template from the original author's [github page](http://mchung.github.com/heroku-buildpack-wordpress/).

The best way to use this project template is to fork it, modify it to your specifications, and then upload it to your Heroku instance (which is how this fork is using it). This fork is used for my own personal [blog](http://blog.richsinn.com).

The rest of the README below is exactly as how it appears in the
original [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project template.

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
