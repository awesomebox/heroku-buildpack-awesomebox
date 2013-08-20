Heroku Buildpack for awesomebox
===============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [awesomebox](https://get.awesomebox.es).

This makes deploying awesomebox apps to Heroku dead simple. From your project directory here's what you'll need to do.

```sh
# Create a new Heroku app that uses this buildpack
heroku create --buildpack https://github.com/mattinsler/heroku-buildpack-awesomebox

# Push your code to Heroku using git
git push heroku master
```

That's it!

### Not a Heroku member?

If you do not already have a Heroku account, [go sign up](https://www.heroku.com/). Then download and install the
[Heroku Toolbelt](https://toolbelt.heroku.com/).

### Not using git?

We can fix that! [Install git](http://git-scm.com/book/en/Getting-Started-Installing-Git). Then, in your project
directory, run this:

```sh
# Initialize git in the current directory
git init

# Add all of the files and directories in this directory
git add .

# Commit these files so that we can push this version to Heroku
git commit -m 'Initial commit'
```

No you're ready to run the `git push heroku master` command from above.
