# lostfilm-rss-parser

1. edit <b>config.yml</b> 
   - add your series
   - add your lostfilm cookie
   - change path to torrents dir
   - change transmission auth data
   - change email sending data and enable it, if you want
   - if you want - change user agent
2. edit <b>run.sh</b> - change path to parser dir
3. make <b>parser.py</b> and <b>run.sh</b> executable (chmod +x)
4. make lostfilm-rss-parser dir writable for crontab user - it's needed for storing log files
5. add <b>run.sh</b> to your crontab
