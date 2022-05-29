# Debian

Debian packages are currently generated with a combination of `nfpm`,
`equivs-build` and `makedeb`. At some point, I might just write my own tool
because none of these do *exactly* what I want.

## TODO

The following falls under what is already available *not* what work is left to
be done.

 - [ ] Move to install kubernetes via latest release and not via apt repository
 - [ ] Find an alternative to `makedeb` that isn't as opinionated (and supports templates?)
 - [ ] Replace `equivs-build` with nfpm
