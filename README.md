# woof-CE-noarch
noarch pet packages

This is a forked version of the pet packages noarch repo that reverts back to frugalpup36

## Adding or Updating packages

You don't even need to use the `git` command line app, if you have write access just go to:

https://github.com/puppylinux-woof-CE/woof-CE-noarch/tree/master/pet_packages-noarch

And click on `Upload files`. Otherwise open a new issue and post a link to the pet package.

You or somebody else must add or update the pkg db entry in:

https://github.com/puppylinux-woof-CE/woof-CE/blob/testing/woof-distro/Packages-puppy-noarch-official

## Info

- Some noarch packages might be modified versions (peasyport), don't (always) assume you have the latest (woofce) version.

- Some noarch packages are deprecated or not in use, if a noarch .pet package is not listed in `Packages-puppy-noarch-official`, it's deprecated (it's probably buggy or has been replaced with something else).

- It's a git repo, it might become too big (git history).

- `Unfortunately` a cleanup operation should happen one day (delete the git history).
  

## DISTRO_PET_REPOS

```
PKG_DOCS_PET_REPOS="
...
z|https://raw.githubusercontent.com/puppylinux-woof-CE/woof-CE/testing/woof-distro/x86/Packages-puppy-common32-official|z
"

PET_REPOS="
...
z|https://raw.githubusercontent.com/puppylinux-woof-CE/woof-CE-noarch/master|Packages-puppy-noarch-official
"
```
