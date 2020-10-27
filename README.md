# push-artifacts
A shell script for pushing build artifacts to a remote Git repository

## Git commit information

Make sure you set up the Git identity before running the script, otherwise
Git will ask you to "tell it who you are". This can be done using `git config`:

```bash
git config --global user.name 'Kaitai Bot'
git config --global user.email 'kaitai-bot@kaitai.io'
```

See [`git commit` > Commit information](https://git-scm.com/docs/git-commit#_commit_information)
for more info.

For _kaitai-io_ repositories, this can be set by running:

```bash
./git_config_kaitai_bot
```
