hermes_cli
==========

Performance Results CLI wrapper

Installation
-----------

To install the CLI, you'll need to first install Ruby.  The clone this repository and run 

    bundle install

Add HERMES_URI to your environment variable, setting it to your api url:

    export HERMES_URI=http://api.myperformanceui.com


Running
-----------

Execute it directly from this repository

    ruby hermes_exec 

Available commands

    ruby hemres_exec list
    ruby hemres_exec list -a repose
    ruby hemres_exec list -a repose -s atom_hopper
    ruby hemres_exec status -a repose
    ruby hemres_exec status -a repose -s atom_hopper
    ruby hemres_exec status -a repose -s atom_hopper -t load
    ruby hemres_exec start -a repose -s atom_hopper -t load {whatever other data i need}
    ruby hemres_exec stop -a repose -s atom_hopper -t load {whatever other data i need}
