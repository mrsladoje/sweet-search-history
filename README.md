# sweet-search history archive

This repo holds the complete, unmodified git history of
[mrsladoje/sweet-search](https://github.com/mrsladoje/sweet-search) as it was on 2026-11-04,
on the `main` branch and all tags.

On 2026-11-04 the main repo's history was rewritten with `git filter-repo` to remove old Rust
build output (`crates/*/target*/` and two native `target/` folders) that had been committed by
mistake. That cut a full clone from 483 MB to 71 MB. Source code was not changed: the final
tree is byte-identical (tree `f139cc782f475915401f52e83bbb19a901bac895`).

- `commit-map.txt`: old commit hash → new commit hash, for every commit.
- `ref-map.txt`: old → new hash for every branch and tag.
