..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _userguide:

CLI Guide
=========

.. contents::

Usage
-----

.. code-block:: bash

    pio [OPTIONS] COMMAND
    platformio [OPTIONS] COMMAND

    # "pio" is the alias of "platformio" command

Options
-------

.. program:: platformio

.. option::
    --no-ansi

Do not print ANSI control characters.

See also :envvar:`PLATFORMIO_NO_ANSI` and :envvar:`PLATFORMIO_FORCE_ANSI`
environment variables.


.. option::
    --version

Show the version of PlatformIO

.. option::
    --help, -h

Show help for the available options and commands

.. code-block:: bash

    $ platformio --help
    $ platformio COMMAND --help


Commands
--------

.. toctree::
    :maxdepth: 2

    platformio account <account/index>
    cmd_boards
    cmd_ci
    cmd_debug
    cmd_device
    cmd_home
    cmd_init
    platformio lib <lib/index>
    platformio platform <platforms/index>
    platformio remote <remote/index>
    cmd_run
    cmd_settings
    cmd_test
    cmd_update
    cmd_upgrade
