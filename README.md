# learned
a modern website

# pyenv
pyenv install 3.14.2
pyenv local 3.14.2

# git
git add .
git status 
git commit -m "...."
git checkout branch-name
git push origin branch-name

git rm --cached

git commit -m "Remove unwanted file"

# poetry
python -m poetry new project-name
cd .\homino\
python -m poetry add package-name

# restart poetry
python -m poetry env activate
(دقت کن که در انتهای آدرس، به جای `activate.bat` نوشتم `Activate.ps1`)

# start project with django
python -m poetry run django-admin startproject core .

# build apps
python -m poetry run django-admin startapp users .
