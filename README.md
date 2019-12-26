# What it is

*CodeDance Folksonomy* is a knowledge base for collaborative tagging of open-source software.

It's permissively licensed and can power analytics engines and knowledge databases, that target open-source software.
As an example, it powers content classification at www.code.dance.
Every day a script runs and pulls from this repository redefining how OSS projects are grouped and displayed at www.code.dance.

# How it works

Every directory in this repository represents a tag that groups several open-source software projects.
A directory (tag) can have subdirectories (subtags).
Thus OSS projects can be organized into a taxonomy similar to how people organize files in nested directories. 

Each directory may contain a CSV file that contains OSS projects data for the corresponding tag, and a `README.md` file that includes a human-friendly description.

Each CSV file is effectively a table.
The table columns are:

- `src_url` - URL for source code repository.
- `vcs`     - Type of a version control system (ex. `git` or `hg`).
- `name`    - User-friendly name of the project.
- `web_url` - URL for the project's website.
- `description` - user-friendly description of the open-source project, appropriate for the context of this tag.

Please send us a pull request to create a new tag, add an OSS project, or fix an inaccuracy. Let's create a better taxonomy for open-source projects. 

Happy coding!
