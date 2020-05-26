# XGit

Shell version git implementation for fun.

## How?

1. do sha1 hash for the contents;
2. maintains the refs, commits, logs, tree, blob objects;
3. basic clis for helping do these routines.

## Known issues

* `gitcontent` result didn't match the raw command execution..
* only works for the first commit..

## Design

Index, Commit, Tree, Blob, Refs.

TODO: implement a simple version index.

TODO: implement the commit with tree and log.

TODO: implement the refs and HEAD/Branch/Tag.

TODO: implement the three-way merge method, for two branch.
