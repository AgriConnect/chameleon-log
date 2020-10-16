============
ChameleonLog
============

Python logging setup library which can choose the best available handler for an environment to produce colored message.

For example, if it detects that the application is running as service under systemd, it will route the logs to journald.
