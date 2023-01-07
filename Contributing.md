# Manual for making editing

Please keep your repository up to date. When your menthor have accepted your pullrequest, gets into Academy repository, not in your fork.

#### 1. Please don't make commits into your repository `master`.

This may cause make changes correctly and lead to conflicts.

#### 2. Please renew `master` before starting new task.

You can renew your repository through Academy repository as follows:

```
# Switch into branch master in your local copy
git checkout master

# Accept modifications from the Academy¹ repository.
git pull academy master

# Send modifications into your fork on Githab
git push
```

¹ `academy` must have link to Academy repository. In case of link' absence, add it:

```
git remote add academy git@github.com:htmlacademy-adaptive/841461-cat-energy-23.git
```

Create branch for new task when you have renewed `master`:

```
git checkout -b module2-task1
```

`module2-task1` is branch name. The correct branch name will be specified in each task description..
--
