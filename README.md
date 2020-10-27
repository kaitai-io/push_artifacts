# push-artifacts
A Bash script for pushing build artifacts to a remote Git repository

## Git commit information

Make sure you set up the Git identity before running the script, otherwise
Git will ask you to "tell it who you are". It can be done using `git config`
or setting these environment variables:

```bash
export GIT_AUTHOR_NAME='Kaitai Bot'
export GIT_AUTHOR_EMAIL='kaitai-bot@kaitai.io'
export GIT_COMMITTER_NAME='Kaitai Bot'
export GIT_COMMITTER_EMAIL='kaitai-bot@kaitai.io'
```

See [`git commit` > Commit information](https://git-scm.com/docs/git-commit#_commit_information)
for more info.

For _kaitai-io_ repositories, this can be set by running:

```bash
./git-config-kaitai-bot
```
