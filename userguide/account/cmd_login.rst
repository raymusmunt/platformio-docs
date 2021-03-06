..  Copyright 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _cmd_account_login:

platformio account login
=========================

.. contents::

Usage
-----

.. code-block:: bash

    platformio account login [OPTIONS]
    pio account login [OPTIONS]

Description
-----------

Log in to :ref:`cmd_account`. If you are not able to provide authentication
credentials manually you can use :envvar:`PLATFORMIO_AUTH_TOKEN`. This is
very useful for :ref:`ci` systems and :ref:`pio_remote` operations .

Options
~~~~~~~

.. program:: platformio account login

.. option::
    --username, -u

User name (E-Mail). You can omit this option and enter E-Mail in Login Wizard
later.

.. option::
    --password, -p

You can omit this option and enter securely password in Login Wizard later.
