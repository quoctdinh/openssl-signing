####
#### openssl genrsa -out privkey.pem 1024
####
#### openssl req -new > cert.csr
#### openssl rsa -in privkey.pem -out key.pem
####
#### Self signing:
> openssl x509 -in cert.csr -out cert.pem -req -signkey key.pem -days 1001
