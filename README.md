# thttpd - PHP fork #
Fork of thttpd (v2.29 of 23May2018).

## Patches ##
This repository contains the original thttpd v2.29 server with very minimal modifications for it to work with modern PHP over CGI. Specifically, it exports two required environment variables for it to work, `REDIRECT_STATUS` and `SCRIPT_FILENAME`.