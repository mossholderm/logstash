This directory contains debugging scripts and files.

000-debug.conf              - Debugging header config. Reads from std in. Make sure you set any appropriate types before running with this.
999-debug.conf              - Logs to stdout with rubydebug enabled.
re-init                     - A bash script that deletes everything from elasticsearch, and restarts logstash and kibana.
ruby-whitelist.conf.sample  - An example of using Ruby for whitelisting.
test_json.log               - A test JSON formatted log.
test_syslog.log             - A test SYSLOG formatted log.
