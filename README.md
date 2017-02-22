Setup monit.

## Included checks:
- restart apache2 if stop
- restart apache2 if monit_check_hostname:monit_check_port/monit_check_request failed 2 times (non 200 http code)
- restart pt-kill if stop
- alert on iowait > 50%
- alert on disk space ending
- alert on la (1min) > 20
- alert on la (5min) > 10
