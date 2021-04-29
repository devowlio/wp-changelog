# tcf-vendor-list-normalize

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.2.0 (2021-04-29)


### feat

* allow to query a single vendor (CU-crwq2r)
* allow to query multiple vendors with the in-argument (CU-ff0zhy)
* allow to return only declarations instead of with metadata (onlyReturnDeclarations, CU-ff0z49)
* compatibility with TCF v2.1 (device storage disclosures, CU-h74vna)
* download and normalize Global Vendor List for TCF compatibility (CU-63ty1t)
* introduce query class to read purposes and vendors (CU-crwq2r)
* persist and query stacks, and calculate best suitable stacks for a given set of declarations (CU-fh0bx6)


### fix

* localize stacks correctly and sort by score (CU-ff0zhy)
* map used declarations to own array instead of removing purposes from original vendor (CU-ff0yvh)
* notices thrown when no vendor given (CU-ff0yvh)
* review 1 (TCF, CU-ff0yck)
* review 2 (CU-ff0yvh)
* review TCF CMP validator (CU-hh395u, CU-hh3dkn)
* use correct language as requested (CU-crwwdx)


### refactor

* create wp-webpack package for WordPress packages and plugins
