# cfunits-docs
Archive store of built HTML documentation for old versions of cfunits

### Background

This repository is designed to house built i.e. HTML-format files defining
the content of the built documentation for older, i.e. not the latest,
versions of the [cfunits](https://github.com/NCAS-CMS/cfunits) library.

Note that the contents of this directory, namely the built HTML documntation
for the older versions, used to live in the core cfunits repository (as
linked above) under `docs/`. They were moved out at version `3.3.6`.


### Structure

This repository is arranged such that the previous versions form the
top-level directories, named according to version (which is equal to
the corresponding branch name minus the inital `v` character), and the
content for the documentation at the given version is contained inside
the relevant directory.

### Updating

**For every cfunits release, the built documentation for the version that
has just been surpassed as the latest by a new release should be moved
here under its own (version name) top-level directory. It should not be
touched at all after that.**
