<pre>
git init
git remote add origin https://gitlab.com/I9503031124034D9_1/1.git
git config --global user.email 'I9503031124034D9@GMAIL.COM'
git config --global user.name '_'
git branch -M main
git config --system --unset credential.helper
--------------------------------------------------------------------
git branch --set-upstream-to=origin/main main
git pull --allow-unrelated-histories
git add .
git commit -m '1'
git push -uf origin main

</pre>