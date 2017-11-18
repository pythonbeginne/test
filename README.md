echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pythonbeginne/test.git
git push -u origin master
git clone git://github.com/django/django.git
