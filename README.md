# What it is

*CodeDance Folksonomy* is a knowledge base for collaborative tagging of open-source software.

It's permissively licensed and can power analytics engines and knowledge databases, that target open-source software.
As an example, it powers content classification at <www.code.dance>.
Every day a script runs and pulls from this repository redefining how OSS projects are grouped and displayed at <www.code.dance>.

# How it works

Every file in this repository (except for the README.md file) represents a tag (category) that groups several open-source software projects.
The filename corresponds to the tag name.

The format of files is CSV, so each file is effectively a table.
The table columns are:

- `src_url` - URL for source code repository.
- `vcs`     - Type of a version control system (ex. `git` or `hg`).
- `name`    - User-friendly name of the project.
- `web_url` - URL for the project's website.
- `description` - user-friendly description of the open-source project, appropriate for the context of this tag.

Please send us a pull request to create a new tag (file) or add projects (rows) to existing files. They help build nicer analytics at <www.code.dance> and other similar projects.

Happy coding!
