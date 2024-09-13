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
  <li><a href="#command-10">git-remote</a></li>
  <li><a href="#command-11">To see remote</a></li>
  <li><a href="#command-12">git-push</a></li>
  <li><a href="#command-13">delete a remote</a></li>
  <li><a href="#command-14">create branch</a></li>
  <li><a href="#command-15">delete branch</a></li>
  <li><a href="#command-16">checkout branch</a></li>
  <li><a href="#command-17">merge a changes</a></li>
  <li><a href="#command-18">gti-clone</a></li>
  <li><a href="#command-19">remote-upstream</a></li>
  <li><a href="#command-20"></a></li>
  <li><a href="#command-21">open</a></li>
  <li><a href="#command-22">clear</a></li>
  <li><a href="#command-23">nano</a></li>
  <li><a href="#command-24">whoami</a></li>
  <li><a href="#command-25">grep</a></li>
</ul>


<h2 id="command-1">ls</h2>
<p>Lists files and directories in the current directory.</p>
<pre><code>ls</code></pre>

<h2 id="command-2">pwd</h2>
<p>Displays the current working directory.</p>
<pre><code>pwd</code></pre>

<h2 id="command-3">mkdir</h2>
<p>Creates a new directory.</p>
<pre><code>mkdir /directory-path/directory-name</code></pre>

<h2 id="command-4">rmdir</h2>
<p>Removes an empty directory.</p>
<pre><code>rmdir /director-path/directory-name</code></pre>

<h2 id="command-5">touch</h2>
<p>Creates an empty file or updates the timestamp of an existing file.</p>
<pre><code>touch file-name</code></pre>

<h2 id="command-6">cd</h2>
<p>Changes the current working directory.</p>
<pre><code>cd /directory-path</code></pre>

<h2 id="command-7">cd ..</h2>
<p>Moves one directory up.</p>
<pre><code>cd ..</code></pre>

<h2 id="command-8">ls -a</h2>
<p> Lists all files, including hidden files.</p>
<pre><code>ls -a</code></pre>

<h2 id="command-9">ls -l</h2>
<p>Lists files in long format with detailed information.</p>
<pre><code>ls -l</code></pre>

<h2 id="command-10">Renaming</h2>
<p>Renames a file.</p>
<pre><code>mv oldname.txt newname.txt</code></pre>

<h2 id="command-11">To move</h2>
<p>Moves a file to a different directory.</p>
<pre><code>mv file.txt /directory-path-we-want-to-move</code></pre>

<h2 id="command-12">Copy File</h2>
<p>Copies a file from one location to another.</p>
<pre><code>cp source.txt destination.txt</code></pre>

<h2 id="command-13">Copy Directory</h2>
<p>Copies the entire directory /source_dir and its contents (including subdirectories) to /dest_dir</p>
<pre><code>cp -r /source_dir /dest_dir</code></pre>

<h2 id="command-14">File Permission</h2>
<p> Changes file permissions recursively to allow full read, write, and execute access to all users.</p>
<pre><code>sudo chmod -R 777 /path</code></pre>

<h2 id="command-15">Find Files</h2>
<p>Finds files with a specific pattern in a directory.</p>
<pre><code>find /path -name "*.txt" </code></pre>

<h2 id="command-16">Curl</h2>
<p>Downloads a file from a URL.</p>
<pre><code>curl -O http://example.com/file.zip</code></pre>

<h2 id="command-17">Update packages</h2>
<p>Updates the package list on Ubuntu/Debian-based systems. </p>
<pre><code>sudo apt update</code></pre>

<h2 id="command-18">Restart</h2>
<p>Reboots the system.</p>
<pre><code>sudo reboot</code></pre>

<h2 id="command-19">Compress as Zip file</h2>
<p>Compresses a file into a zip archive.</p>
<pre><code>zip [zip-name] [the-file-name-you-want-to-compress]</code></pre>

<h2 id="command-20">Extract Zip File</h2>
<p>Extracts files from a zip archive.</p>
<pre><code>unzip [zip-file-name]</code></pre>

<h2 id="command-21">Open</h2>
<p>Open a file.</p>
<pre><code>open filename</code></pre>

<h2 id="command-22">clear</h2>
<p>The clear command is used to clear the terminal screen</p>
<pre><code>clear</code></pre>

<h2 id="command-23">nano</h2>
<p> it opens for editing. If it doesn't exist, nano creates a new file.</p>
<pre><code>nano file-name</code></pre>

<h2 id="command-24">whoami</h2>
<p>It print the current username</p>
<pre><code>pwd</code></pre>

<h2 id="command-25">grep [options] pattern [file]</h2>
<p>The grep command searches for a specific pattern (text) within files or output and displays matching lines.</p>
<pre><code>grep "hello" file.txt</code></pre>
