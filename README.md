# apt-packages-copy

This shell script aim to get easier to move from a debian server to another one, by reinstalling the same package on the new server.

## usage

Note that the two servers must be in the same debian version, and the new server must have an admin access in ssh on the old one.

./apt-copy-packages my_new_server_ip_or_dns [user to connect to]
