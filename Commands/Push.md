# git push

When you have a [remote](./Remote.md) set up you'll need to begin to move [commits](./Commit.md) to the remote. This canbe done with the command `git push`.

You can attach a name and a branch name to you command to specify where you're pushing to.

```
git push origin main
```

This command wiil push the **main** branch to the remote called **origin**. 
This means any commits that are in your local will be **pushed** to the remote.

### Upstream Tracking

Instead of including the name of the remote ad the branch you're on every time, you can set local bracnhes to track an upstream branch. This means you can tell the branch to push to its assigned remove branch by using the command `git push`.

Before doing so, you'll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and ot will function the same way.

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to home](../README.md)