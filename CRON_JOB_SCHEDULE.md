# Schedule a Job using cron
```
$ crontab -e
*/2 * * * * /root/sync_git_repo.sh

$ crontab -l

$ tail tail -f /var/log/cron

```