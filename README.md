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
    ruby hemres_exec list repose
    ruby hemres_exec list repose translation
    ruby hemres_exec status repose
    ruby hemres_exec status repose translation
    ruby hemres_exec status repose translation load
    ruby hemres_exec start repose translation load {whatever other data I need}
    ruby hemres_exec stats repose translation
