# OBF API Certificate Generation Script

## Dependencies (Ubuntu 16.10)

* libfile-slurp-perl
* libcrypt-openssl-rsa-perl


## Running

* Write your Origanisation ID into *config/id*
* Go to https://openbadgefactory.com/c/client/my/edit2/apikey, generate a key by klicking the button and look at the GET request that fires.
* Save its '\_' parameter in *config/counter* and the session part of the 'Cookie' header into *config/session*
* `./get-certificate`
