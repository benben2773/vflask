# vflask


https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iv-database


# How to setup smtp local to test
python -m smtpd -n -c DebuggingServer localhost:8025

# from another flask running window
export MAIL_SERVER=localhost
export MAIL_PORT=8025