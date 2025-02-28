############
Contributing
############

*******
License
*******

By contributing to this repository/project you are licensing your contributions
under `MIT`_ license.

*****************
Coding Guidelines
*****************

- Limit characters to 79 characters per line
- Add one empty line at the end of a file (POSIX 3.206 Line)
- Python files must follow the rules defined in `pyproject.toml`
- Python files must have the following header

  .. code-block:: python
     :linenos:

     #!/usr/bin/env python
     # encoding: utf-8

     # SPDX-License-Identifier: MIT

- lua files must have the following header

  .. code-block:: lua
     :linenos:

     #!/usr/bin/env lua

     -- SPDX-License-Identifier: MIT

- C/C++ files must have the following header

  .. code-block:: C
     :linenos:

     /* SPDX-License-Identifier: MIT */

.. _MIT: https://opensource.org/licenses/MIT
