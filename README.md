# Show Git Information In Bash Prompt

The snippet found here in the ```.bashrc``` file, when added to your own, will show the current git branch as well as any statuses available.

With no statuses:
```bash
user@host:~/path/to/git/repo {bit-branch-name}$
```

When there has been a change to a file:
```bash
user@host:~/path/to/git/repo {bit-branch-name !}$
```

When there are untracked files in the repo:
```bash
user@host:~/path/to/git/repo {bit-branch-name ?}$
```

When there are both changes and untracked files:
```bash
user@host:~/path/to/git/repo {bit-branch-name !?}$
```

Try it out!