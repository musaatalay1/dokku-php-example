slim
====

* currently unstable while I'm adjusting the nginx config to run out of an app folder, fork this at your own risk ;)

a basic php app on the slim microframework ready to be pushed to dokku!

really, there is not much here. copypasterino from the heroku nginx config and composer with a slim install. pull requests welcome :)

you need to commit the composer.lock file. to update you will need to run a composer update if you would like to update slim and then deploy.

the .json is set to 2.*. last time i updated this lock was set to 2.4.3. if you want to upgrade to the lastest version of slim you will need to rebuild the lock file with composer.


todo: 

1. need to move the app to a subfolder to prevent people from pulling down config. While this is open source it's not super important but would be a best practice.

