glua.me
=======

The aim of this site is to be the portal for Garry's Mod Lua coders.

How can I help?
------------------
Please don't push directly to this repo. File a pull-request so people can look over your changes. This repo does autodeploy to the main website and right now you are trusted not to fuck up.

Steps to a successful pull-request
- Test your changes locally
- File it as a pull-request don't commit straight to the repo
- Get someone to look over your changes.

If you aren't sure speak to someone in the GModCoders chat.

Wait? How does the docs directory get here?
------------------
We use DeployHQ to auto deploy from this repo the webserver. After the site has been updated it runs the command:

    rm -Rf %path%/docs && git clone -b gh-pages https://github.com/samuelmaddock/glua-docs.git %path%/docs
    
as the site gets more complicated the build process may need to change.
