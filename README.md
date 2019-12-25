# What it is

*CodeDance Folksonomy* is a knowledge base for collaborative tagging of open-source software.

It's permissively licensed and can power analytics engines and knowledge databases, that target open-source software.
As an example, it powers content classification at www.code.dance.
Every day a script runs and pulls from this repository redefining how OSS projects are grouped and displayed at www.code.dance.

# How it works

Every file in this repository (except for the README.md and LICENSE files) represents a tag (category) that groups several open-source software projects.
The filename corresponds to the tag name.

The format of files is CSV, so each file is effectively a table.
The table columns are:

- `src_url` - URL for source code repository.
- `vcs`     - Type of a version control system (ex. `git` or `hg`).
- `name`    - User-friendly name of the project.
- `web_url` - URL for the project's website.
- `description` - user-friendly description of the open-source project, appropriate for the context of this tag.

Each directory in this repository represents a grouping of tags. Thus OSS projects can be organized into a taxonomy similar to how people usually organize files in nested directories. Each directory will contain a single README.md file that will describe what that tag means.

Please send us a pull request to create a new tag (file or directory) or add projects (rows) to existing files. Let's create a better taxonomy of open-source projects to serve discovery and analysis at resources like www.code.dance and beyond.

Happy coding!
