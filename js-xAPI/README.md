Setup
`````
$ npm install -g http-server
$ git clone https://github.com/adlnet/xAPIWrapper.git
$ openssl req -x509 -sha256 -nodes -days 30 -newkey rsa:2048 -keyout privateKey.key -out certificate.crt
$ http-server --ssl --cert local-dev-ssl-certificate.crt --key privateKey.key --cors

Check xAPI version in `xAPIWrapper/src/xapiwrapper.js` is equal to the version supported by your LRS,
default at time of this reference is: `XAPIWrapper.prototype.xapiVersion = "1.0.1";`

Open `https://localhost:8080` in a browser with console open.
