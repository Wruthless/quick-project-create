# quick-project-create

A script that sets up a basic Python project for you. It automates the creation of a directory, virtual environment, and git repository. I typically follow these steps when using the script:

1. Execute the script
2. Create a repo with the same name on GitHub
3. Copy the URL of the repo
4. Utilize the URL to set your origin

<pre>
$> git remote add origin &lt;git@github.com:Xxxxx/xxx-xxx-xxx.git&gt;
</pre>

5. Verify the repo

<pre>
$> git remote -v
</pre>

6. Push and set the upstream master

<pre>
$> git push --set-upstream origin master
</pre>

I will eventually automate the remaining manual steps, eventually :-)
