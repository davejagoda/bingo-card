bingo-card
==========

# prerequisites

## This software should be installed on your computer:

- `curl`
- `git`
- nodejs (`node` and `npm`)
- expressjs (`express`)
- heroku toolbelt (`heroku`)

## You should have at least the following accounts:

- github
- heroku

# instructions

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

`heroku auth:whoami`

*previous command shows that you are the right heroku user if you have more than one heroku account*

`heroku create bingo-card`

`express bingo-card`

`mv -i bingo-card/* .`

`npm install`

*much output from the npm install of dependencies*
