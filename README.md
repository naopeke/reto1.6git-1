# reto1.6git-1
<h1>Git</h1>

<h3>Configuración de GIT</h3>
<p>$ git config --global user.name "John Doe"</p>
<p>$ git config --global user.email johndoe@example.com</p>

<h3>Configución de GIT</h3>
<p>$ git config --list<br>user.name=Scott Chacon<br>useremail=schacon@gmail.com<br>color.status=auto<br>color.branch=auto<br>color.interactive=auto<br>color.diff=auto<br>...<br>$ git help config</p>

<h3>GIT INIT</h3>
<p>$ git init</p>
<p>$ git clone https://github.com/username/repository_name.git</p>

<h3>COMMANDS</h3>
<p>$ git add .</p>
<p>$ git commit -m "write your comment here"</p>
<p>$ git push </p>
<p>$ git pull https://github.com/username/repository_name.git</p>

<h3>RESET</h3>
<p>$ git reset --soft HEAD~ <br>$ git reset --mixed HEAD~<br>$ git reset --hard HEAD~</p>

<h3>GIT BRANCH</h3>
<p>$ git branch new_branch_name</p>
<p>$ git branch</p>
<p>$ git checkout branch_name</p>


<h1>GIT MERGE</h1>
<p>$ git checkout main<br>$ git merge new_branch_name</p>

<h1>GIT IGNORE</h1>
<p>$ touch .git ignore<br>$ git status<br>$ vi .gitignore</p>
<p>shift:wq (write & quit</p>
