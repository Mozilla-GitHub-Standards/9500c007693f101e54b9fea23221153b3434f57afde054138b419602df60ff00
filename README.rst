Perform operations against Taskcluster API.
===========================================================================

Installation
------------

- ``virtualenv venv``
- ``source venv/bin/activate``
- ``pip install tctalker``

Configs specification
---------------------

Configs can served via json config file (check config.json.sample included within this repo)

Usage
-----

Usage example following Pypi installation:

- ``tctalker --verbose --conf config.json report_completed $taskid1 $taskid2 [...]``
- ``tctalker --conf config.json cancel $taskid3``
- ``tctalker --conf rerun $taskid4``

