hermes_cli
==========

Performance Results CLI wrapper

Installation
-----------

To install the CLI, you'll need to first install Ruby.  The clone this repository and run 

    bundle install

Running
-----------
You can either add hermes_cli/bin/hermes_exec to your $PATH or execute it directly from this repository's bin directory

    ./bin/hermes_exec 

Available commands

    ./bin/hemres_exec list
    ./bin/hemres_exec list -a repose
    ./bin/hemres_exec list -a repose -s atom_hopper
    ./bin/hemres_exec status -a repose
    ./bin/hemres_exec status -a repose -s atom_hopper
    ./bin/hemres_exec status -a repose -s atom_hopper -t load
    ./bin/hemres_exec start -a repose -s atom_hopper -t load {whatever other data i need}
    ./bin/hemres_exec stop -a repose -s atom_hopper -t load {whatever other data i need}
