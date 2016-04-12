This directory contains debugging scripts and files.

19-mark.conf        - A test Logstash configuration.
check-ls            - A bash script to test a configuration file.
debug-01.conf       - A header for the above script, causes Logstash to use STDIN for reading the log.
debug-30.conf       - A footer for check-ls.
re-init             - A bash script that deletes everything from elasticsearch, and restarts logstash and kibana.
ruby-whitelist.conf - An example of using Ruby for whitelisting.
test_json.log       - A test JSON formatted log.
test_syslog.log     - A test SYSLOG formatted log.
