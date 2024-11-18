# Salesforce OSS template

Template files for open source projects at Salesforce. We suggest customizing the following files before use:

- CONTRIBUTING.md

For more information about the license, see [license_info.md](license_info.md).

## Usage, automated

All files must be placed at the top level of your repository. Copy the following files into your project:

- CODE_OF_CONDUCT.md
- CODEOWNERS
- CONTRIBUTING.md
- LICENSE.txt
- SECURITY.md

This task can be accomplished by running these commands in a terminal that has [curl](https://curl.se/) installed:

```term
curl --remote-name --fail https://raw.githubusercontent.com/salesforce/oss-template/refs/heads/main/CODE_OF_CONDUCT.md &&
curl --remote-name --fail https://raw.githubusercontent.com/salesforce/oss-template/refs/heads/main/CODEOWNERS
curl --remote-name --fail https://raw.githubusercontent.com/salesforce/oss-template/refs/heads/main/CONTRIBUTING.md
curl --remote-name --fail https://raw.githubusercontent.com/salesforce/oss-template/refs/heads/main/LICENSE.txt
curl --remote-name --fail https://raw.githubusercontent.com/salesforce/oss-template/refs/heads/main/SECURITY.md
```

Inspect the files, and ensure the downloads succeeded (below `$` indicates a command was run in a terminal/command prompt):

```term
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	CODEOWNERS
	CODE_OF_CONDUCT.md
	CONTRIBUTING.md
	LICENSE.txt
	SECURITY.md
```

Customize the following files with project-specific information:

- CONTRIBUTING.md

Replace lines containing HTML comments with the desired contents. For example, if your project was named "V2MOM Analyzer," you could replace this:

```
# Contributing Guide <!-- For {NAME OF PROJECT} -->
```

With this:

```
# Contributing Guide V2MOM Analyzer
```

Commit the results to git.
