# Splunk-log-alert-using-C-Script
Using my custom made C++ Script to generate alerts on a Splunk configuration. 

This C++ script made by me reads a  log file (system_logs.txt) line by line, searching for the keyword "ERROR." If an "ERROR" is found, it writes an alert message to a log file (splunk_alerts.log) and prints the alert to the console. The script stops after the first "ERROR" is detected. It is designed to simulate alert generation based on log file content, which could be useful for testing or checking log monitoring systems.
