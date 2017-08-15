# venv-openstack-hook
virtualenvwrapper hook to activate/target different openstack clusters/auths

Usage:
Add postactivate and predeactivate to ~/.virtualenvs then make a new virtualenv.
Copy your openstackrc.sh file into this new $VIRTUALENV_HOME/bin/.  Now, when
you activate this virtualenv, your openstack credentials will be exported to
your environment.
