# Clustered Share

THIS IS NOT WORKING.

Proposed next step is to setup Apache httpd with mod_jk to handle routing/stickiness.

It appears that the session is reset when failing over so you are forced to login even
though we have setup Tomcat Session Sync.

`docker-compose.yml` is based off the `7.1.N-docker-compose.yml` file in this directory.
