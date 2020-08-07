# Notes on testing webfinger

* Must specify correct requested content type
* Must provide the account as URL argument

E.g.

curl -v -H 'Accept: application/jrd+json, application/xrd+xml;q=0.9' \
http://ubos-dev/next/public.php?service=webfinger\&resource=acct:admin@localhost


