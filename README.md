# designa0

Create a new repository on the command line

	git init
	git add README.md
	git commit -m "first readme"
	git remote add origin https://github.com/inscae/designa0.git
	git push -u origin master

github update

	echo "# designa1" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -a
	git branch -M main
	git remote add origin https://github.com/inscae/designa0.git
	git push -u origin main

or push an existing repository from the commande line

	git remote add origin https://github.com/inscae/designa0.git
	git push -u origin master

github update
	
	git remote add origin https://github.com/inscae/designa0.git
	git branch -M main
	git push -u origin main

La configuration de `git`, exécute les deux commandes:

	git config --global user.name "Name github"
	git config --global user.email "user@email.com"

La commande `git config --list` listera les paramètres.

Pour connître le nom d'utilisateur, tapez en ligne de commande:

	git config user.name

Pour connître l'email, tapez en ligne de commande:

	git config user.email