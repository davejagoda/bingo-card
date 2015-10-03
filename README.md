bingo-card
==========

`mkdir bingo-card`

`cd bingo-card`

`curl -d '{"name": "bingo-card"}' -H X-GitHub-OTP:123456 -u davejagoda https://api.github.com/user/repos`

*much output from the creation of the github repo*

`git init`

`git remote add origin git@github.com:davejagoda/bingo-card.git`

`echo -e "# emacs\n*~" > .gitignore`

`git add .gitignore`

`git commit -m "add .gitignore"`

`git push -u origin master`

`heroku auth`

*previous command shows that you are the right heroku user if you have more than one heroku account*

`heroku create bingo-card`

`npm init`

*accept defaults except for description, keywords, and author*

`npm install express --save`

*much output from the installation of the express package*
