# sm_manager
Starmade Server Management Script

Simple Starmade-Server management script.
Written in Shell script.

Description:
Server will be started in a screen session.
Commands and notices about updates, restart and stop will be sent to online players.
It will also dump the logs on any shutdown/crash/restart to a log directory.

Variables kept global:
- names for status files
- names for config files
- server1 to server5 path
- logpath
- update source paths

(see: /sm_config.cfg)

Variables kept per server:
- name (displayed in script)
- JVM minmemory
- JVM maxmemory
- port
- update source channel
- screen name

(see: /starmade/sm_settings.cfg)

Current features by console:
- start server
- stop server
- restart server
- update server


Todo:
- automate updates
- rewrite to cronjob triggered script
  (external crash detection)
