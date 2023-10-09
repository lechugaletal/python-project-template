# python-project-template

Low dependency, simple to start template for python3 projects.

## What's in the bundle?

 * [🗃️] Project directory structure basis for every python3 app:
   * The ``src/config.d`` should contain environment variable config and sensitive data config files.
   * The ``src/models`` shpuld contain any object schema defined for the project.
   * Other project directories considered but maybe less widely used are: ``src/routers`` and ``src/public``. Keep in mind that those can be useful for Flask projects!
 * [🕵️] A ``.gitignore`` file with defaults for python3 tmp files and sensitive data.
 * [📜] The Unilicense as the basis for projects.
 * [⤵️] A ``requirements.txt`` containing project dependencies.
 * [🔧] A ``Makefile`` with a default instruction set.
 * [📄] And last but not least... this README.md


## Maybees...

 * Generate documentation with [MkDocs](https://www.mkdocs.org/). Although it can be useful for most cases, the idea behind this template is to keep python3 dependencies to a minimum.
