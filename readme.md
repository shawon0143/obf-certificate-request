# OBF API Certificate Generation Script

A simple ruby script to generate a Certificate for the [Open Badge Factory REST API](https://openbadgefactory.com/developers/#open-badge-factory-rest-api).

## Dependencies (Ubuntu 16.10)

* libfile-slurp-perl
* libcrypt-openssl-rsa-perl


## Useage

* Write your Origanisation ID into a file *config/id*
* Go to https://openbadgefactory.com/c/client/my/edit2/apikey, generate a key by klicking the button and write the key to a file *config/api_key*
* Generate a certificate by invoking `./get-certificate`

Your private key will be written to *obf.key* and your certificate will be written to STDOUT so you can pipe it anywhere you want.


## Ping

You can test your certificate with the *ping* script. Provide it with the path to your certificate as an argument: `./ping [CERTIFICATE]`
