# Github-Commands

<h2>Table of Contents</h2>
<ul>
  <li><a href="#command-1">git-add</a></li>
  <li><a href="#command-2">git-status</a></li>
  <li><a href="#command-3">git-commit</a></li>
  <li><a href="#command-4">git-log</a></li>
  <li><a href="#command-5">git-reset</a></li>
  <li><a href="#command-6">git-stash</a></li>
  <li><a href="#command-7">stash-pop</a></li>
  <li><a href="#command-8">stash-clear</a></li>
  <li><a href="#command-9">git-initialize</a></li>
  <li><a href="#command-10">Add a remote</a></li>
  <li><a href="#command-11">To see remote</a></li>
  <li><a href="#command-12">git-push</a></li>
  <li><a href="#command-13">delete a remote</a></li>
  <li><a href="#command-14">create branch</a></li>
  <li><a href="#command-15">delete branch</a></li>
   <li><a href="#command-16">delete remote branch</a></li>
  <li><a href="#command-17">checkout branch</a></li>
  <li><a href="#command-18">merge a changes</a></li>
  <li><a href="#command-19">gti-clone</a></li>
  <li><a href="#command-20">remote-upstream</a></li>
  <li><a href="#command-21">git-pull</a></li>
</ul>


<h2 id="command-1">git-add</h2> 
<p>Adds files to the staging area in preparation for a commit.To add all files use ( . )</p> 
<pre><code>git add (file-or-directory)</code></pre>
  
<h2 id="command-2">git-status</h2> 
<p>Displays the current state of the working directory and staging area, showing which changes have been staged, modified, or are untracked.</p> <pre><code>git status</code></pre>

<h2 id="command-3">git-commit</h2> 
<p>Records changes to the repository with a descriptive message.</p> 
<pre><code>git commit -m "Your commit message"</code></pre>

<h2 id="command-4">git-log</h2> 
<p>Shows the commit history of the repository.</p> 
<pre><code>git log</code></pre>

<h2 id="command-5">git-reset</h2> 
<p>Resets the current HEAD to a specified state, either by un-staging changes, or resetting the working directory.</p>
<pre><code>git reset (commit-hash-id)</code></pre>
  
<h2 id="command-6">git-stash</h2> 
<p>Saves the changes in the working directory temporarily, so you can switch to a different branch without committing the changes.</p> <pre><code>git stash</code></pre>

<h2 id="command-7">stash-pop</h2> 
<p>Restores the most recently stashed changes and removes them from the stash list.</p> 
<pre><code>git stash pop</code></pre>

<h2 id="command-8">stash-clear</h2> 
<p>Clears all stashes, removing them from the stash list.</p>
<pre><code>git stash clear</code></pre>

<h2 id="command-9">git-initialize</h2> 
<p>Initializes a new Git repository in the current directory.
</p> <pre><code>git init</code></pre>

<h2 id="command-10">Add a remote</h2> 
<p>Adds a remote repository URL to your local repository.</p> 
<pre><code>git remote add origin (remote-url)</code></pre>
  
<h2 id="command-11">To see remote</h2> 
<p>Displays the list of remote repositories associated with the local repository.</p> 
<pre><code>git remote -v</code></pre>

<h2 id="command-12">git-push</h2> 
<p>Uploads local commits to a remote repository.</p> 
<pre><code>git push origin (branch-name) </code></pre>
  
<h2 id="command-13">delete a remote</h2> 
<p>Removes a remote repository from the local configuration.</p> 
<pre><code>git remote remove (remote-name) </code></pre>
  
<h2 id="command-14">create branch</h2> 
<p>Creates a new branch.</p> 
<pre><code>git branch (branch-name) </code></pre>
  
<h2 id="command-15">delete branch</h2>
<p>Deletes a local branch.</p> 
<pre><code>git branch -d (branch-name) </code></pre>
  
<h2 id="command-16">delete remote branch</h2>
<p>This command deletes a branch from a remote repository.</p> 
<pre><code>git push origin --delete (branch-name) </code></pre>
  
<h2 id="command-17">checkout branch</h2> 
<p>Switches to the specified branch or restores files in the working directory to a specific commit.</p>
<pre><code>git checkout (branch-name) </code></pre>
  
<h2 id="command-18">merge changes</h2> 
<p>Merges changes from a specified branch into the current branch.</p> 
<pre><code>git merge (branch-name) </code></pre>
  
<h2 id="command-19">git-clone</h2> 
<p>Clones a remote repository to your local machine.</p> 
<pre><code>git clone (repository-url) </code></pre>
  
<h2 id="command-20">remote-upstream</h2> 
<p>Adds a secondary remote repository (usually for a fork) to your local repository.</p>
<pre><code>git remote add upstream (upstream-repo-url) </code></pre>
  
<h2 id="command-21">git-pull</h2> 
<p>Fetches changes from a remote repository and merges them into your current branch.</p> 
<pre><code>git pull origin (branch-name) </code></pre>
