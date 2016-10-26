# OBF API Certificate Generation Script

## Dependencies (Ubuntu 16.10)

* libfile-slurp-perl
* libcrypt-openssl-rsa-perl


## Running

* Write your Origanisation ID into *config/id*
* Go to https://openbadgefactory.com/c/client/my/edit2/apikey, generate a key by klicking the button and write the key to *config/api_key*
* Generate a certificate by invoking `./get-certificate`
