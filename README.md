# nginx vhost configurations

Collection of various helpful nginx vhost configurations.

## force_https.conf

The canonical http->https redirection vhost.

## myip.conf

This vhost returns the IP address of the requester in plaintext, thus implementing a "myip" service in plain nginx without CGI.

## connectivitiy_checks.conf

This is a collection of various vhosts faking connectivity check servers.
In combination with a custom dns server, one can redirect connectivity check requests by various vendors. This might be used to keep connectivity checking working but never leave the own network.
