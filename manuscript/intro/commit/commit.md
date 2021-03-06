# Make and edit a commit

**A commit is a snapshot of every file in your project folder**, along with some metadata such as when the commit was made, who made it, and a short message describing the reasoning behind the work.  **A repository is just a pile of commits**. Some of git's more powerful features can make it seem like there must be something more complex happening, but it really is that simple.

Each row in the `History` table (the bottom of the screen) represents a commit.  If you just created an empty repository, then you won't have much to look at yet, but you will soon!  If you click a commit, you can see the names of files that were created, deleted, or changed between that commit and the previous commit.

![Click a commit](commit-browse-commits.mp4)

If you click one of the changed files, you can see the actual contents of the file and how it changed.

![Created, deleted, and changed files](commit-browse-files.mp4)

You can also see metadata about who made the commit, when, and why.

![Who, what, when, why](commit-who-when-what-why.mp4)

If you double-click a commit, it will open the snapshot as a folder, so that you can see exactly what the project folder looked like when the snapshot was taken.

![Open as a folder](commit-open-folder.mp4)

Now you're going to make your own commit.  In the list of commits at the bottom, there is always a special row for something called the "working copy", often abbreviated "WC".  **The working copy is a draft of the next commit you're going to make**.  If you're looking at the working copy, then this button will say `Commit`.  If it doesn't say `Commit`, then it will say `Go to WC`, and if you click it, it will take you to the working copy.

![Go to the WC](commit-goto-wc.mp4)

Once you're at the working copy, the `Changed files` section will show you which files you have modified in your project directory.  To make sure that it is up-to-date, you can hit the refresh button.  To make a commit, all you need to do is check the box for which files you'd like to commit, and type in a commit message which explains the reasoning behind your changes.

![Make a commit](commit-make.mp4)

## Edit your commit

Pedants will tell you that it's impossible to edit a commit.  Pedantically speaking that is true - however, you *can* make a brand new commit with the same snapshot of files but a different commit message, which sure feels a lot like an edit.  Right-click a commit and select `Edit metadata` to do this.

![Edit a commit](commit-edit.mp4)

There are some rules about when you should and shouldn't change commits in this way, which luckily will turn out to be obvious when you understand git a little more.  For now, pretend that you can only change your most recent commit.  If you stick with us for a little longer then you'll understand fully when you can and can't "change" a commit.

## Set your username

Every time you make a commit, it will be tagged with your name and email.  That way when you share your commits, your colleagues will be able to know who to contact if they'd like to discuss a particular change.  You only have to set your username once, and it will be set for all the commits you make to every repository.

Click the command console ![command console icon](command-console.png), then select `Config library`.  Once that is open, select `Git` from the tree at left and type in your name and email in the **Committer** box.

![Set username](commit-set-username.mp4)

Now that you know your way around commits, we can take a look at [branches](../../branches/branches.md).
