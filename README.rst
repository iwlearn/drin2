Buildout config to create the Plone instance for the updated DRIN site.

This buildout was created by starting from the Plone 4.3 Unified Installer.
The resulting configuration was edited and checked into git. 

The following steps should help you get started::

    mkdir -p zope/drin2/zeocluster
    cd zope/drin2/zeocluster
    git clone git@github.com:iwlearn/drin2.git .
    virtualenv .
    ./bin/pip install zc.buildout==2.4.3
    ./bin/buildout -N -c develop.cfg

