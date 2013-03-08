Simplest possible Heroku clockwork deploy:
==========================================

    git push heroku master
    heroku config:set SERVICENARC_SENDMAIL_TZ="MST" SERVICENARC_SENDMAIL_TIME="7:45" SERVICENARC_DOMAIN_NAME="put.domainname.here"
    heroku scale watcher=1