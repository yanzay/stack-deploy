# Changelog

#### Version 0.3.0.0

New Features:

- Added run-once tasks

#### Version 0.2.1.0

New Features:

- Added possibility to pass arbitrary variables to run command
- Added possibility to skip applications while running a stack
- Added possibility to pass global variables during server start

Improvements:

- Various bug fixes
- Exposed more stack variables for datastax-enterprise-mesos
- Structure context with variable precendence (global, arbitrary, stack)
- All Mesos and Marathon tasks run are now labeled with stack and zone names

#### Version 0.2.0.1

New Features:

- Changed Application.Tasks to be ordered map

Improvements:

- Test coverage
- Readme for task runners
- Fixed some data races

#### Version 0.1.0.0

Basic functionality