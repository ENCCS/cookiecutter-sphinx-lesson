{{cookiecutter.lesson_name}}
{{ '=' * cookiecutter.lesson_name|count }}


Intro



.. prereq::

   prerequisites



.. csv-table::
   :widths: auto
   :delim: ;

   20 min ; :doc:`filename`


.. toctree::
   :maxdepth: 1
   :caption: The lesson


.. toctree::
   :maxdepth: 1
   :caption: Reference

   quick-reference
   guide



.. _learner-personas:

Who is the course for?
----------------------





About the course
----------------






See also
--------





Credits
-------

The lesson file structure and browsing layout is inspired by and derived from
`work <https://github.com/coderefinery/sphinx-lesson>`_ by `CodeRefinery
<https://coderefinery.org/>`_ licensed under the `MIT license
<http://opensource.org/licenses/mit-license.html>`_. We have copied and adapted
most of their license text.

Instructional Material
^^^^^^^^^^^^^^^^^^^^^^

This instructional material is made available under the
{% if cookiecutter.lesson_license == 'CC-BY-4.0' -%}
`Creative Commons Attribution license (CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`_.
The following is a human-readable summary of (and not a substitute for) the
`full legal text of the CC-BY-4.0 license
<https://creativecommons.org/licenses/by/4.0/legalcode>`_.
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) {{cookiecutter.full_name}} and individual contributors and, where practical, linking
  to `<{{cookiecutter.home_page}}>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by/4.0/>`_, and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception
  or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.
{% elif cookiecutter.lesson_license == 'CC-BY-SA-4.0' %}
`Creative Commons Attribution-ShareAlike license (CC-BY-SA-4.0) <https://creativecommons.org/licenses/by-sa/4.0/>`_.
The following is a human-readable summary of (and not a substitute for) the
`full legal text of the CC-BY-SA-4.0 license
<https://creativecommons.org/licenses/by-sa/4.0/legalcode>`_.
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) {{cookiecutter.full_name}} and
  individual contributors and, where practical, linking to
  `<{{cookiecutter.home_page}}>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by-sa/4.0/>`_, and indicate if changes
  were made. You may do so in any reasonable manner, but not in any way that
  suggests the licensor endorses you or your use.
- **ShareAlike** - If you remix, transform, or build upon the material, you must
  distribute your contributions under the same license as the original.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception
  or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.
{% endif %}


Software
^^^^^^^^

Except where otherwise noted, the example programs and other software provided
with this repository are made available under the `OSI <http://opensource.org/>`_-approved
{% if cookiecutter.code_license == 'MIT' -%}
`MIT license <https://opensource.org/licenses/mit-license.html>`_.
{% elif cookiecutter.code_license == 'BSD-3' %}
`BSD 3-clause license <https://opensource.org/licenses/BSD-3-Clause>`_.
{% elif cookiecutter.code_license == 'Apache Software License 2.0' -%}
`Apache License 2.0 <https://opensource.org/licenses/Apache-2.0>`_.
{% elif cookiecutter.code_license == 'Mozilla Public License 2.0' -%}
`Mozilla Public License 2.0 <https://opensource.org/licenses/MPL-2.0>`_.
{% endif %}
