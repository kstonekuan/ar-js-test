# ar-js-test

Testing AR.js capabilities.

## Host locally

https://stackoverflow.com/questions/35127383/npm-http-server-with-ssl

```bash
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
http-server -S -C cert.pem -o
```