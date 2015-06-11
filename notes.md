## APM (atom package manager)
Is installed by default and added to the path
```bash
apm help install
# install a package
apm install <package_name>
# install specific version of a package
apm install <package_name>@<package_version>
# See more info about a package before installing(github link, # of dls)
apm view git-grep
# Fuzzy search package
apm search coffee
```

## Projects

There is no proper project support under atom yet.

We open a project folder using explorer, then the command prompt, then atom.

1. Navigate into the project folder using explorer.
2. `alt+d`, `cmd`, `atom .`
