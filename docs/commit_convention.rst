commit convention
=================

format
------

.. code-block:: text

    <component>: <short description>

- use lowercase component names
- keep descriptions short and clear
- do not end descriptions with a period
- describe what was changed

examples
--------

.. code-block:: text

    refactor: change get -> post petition for logout
    refactor: only accept post petitions for logout

commit body
-----------

for larger changes add a blank line after the subject and explain what changed

.. code-block:: text

    refactor: only accept post petitions for logout

    Restrict the logout endpoint to POST requests instead of GET
    to prevent unintended logouts.
