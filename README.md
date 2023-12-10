# lastpass-cli.bash_completion

Fork of the [lastpass-cli](https://github.com/lastpass/lastpass-cli) bash completion
script.  Fixes the deprecation notice/error for `egrep` and replaces it with `grep -E`.

Multiple pull requests have been submitted to the original repo, but none have been
merged.  The original repo is still being maintained, but the bash completion
script is not.

It appears that this issue will not be resolved in the original repo until `egrep`
is removed by the `grep` maintainers and actually breaks the script.
