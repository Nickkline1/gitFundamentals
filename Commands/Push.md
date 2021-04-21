# git Push
When you have a [remote](./REMOTE.md) set up, you'll need to begin to move [commits](./COMMIT.md) to the remote. This can be done with the command `git push`.

You can attach a name and branch name to your command to specify where you're pushing to. 

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. 
This means any commits that are in your local will be **pushed** to the remote.

### Upstream Tracking

Instead of including the name of the remote and the brance you're on every time, you can set local brances to track an upstream branch.
This means you can tell the branch to pus to it's addisgned upstream remote branch by using the command `git push`. 

Before doing so, youll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will function the same way.

## Resources

- [Git Push Documentation](https://got-scm.com/docs/git-push)
---
[Back to home](../Readme.me)

