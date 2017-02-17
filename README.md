figo encryption example
================

This example demonstrates how to encrypt user credentials using figo's public key and JWE.


### Why?
----------------

figo's API allows to send encrypted user credentials using JWE ([click here for more infos on JWE](https://tools.ietf.org/html/rfc7516)).
Unfortunately the Webcrypto support is limited in some browsers(Safari, Internet Explorer).


### Libraries
----------------

Three libraries where used in order to get things done

* js-jose [https://github.com/square/js-jose](https://github.com/square/js-jose)

JavaScript library to encrypt/decrypt data in JSON Web Encryption (JWE) format.

* webcrypto-shim [https://github.com/vibornoff/webcrypto-shim](https://github.com/vibornoff/webcrypto-shim)

Web Cryptography API shim for legacy browsers

* jsrsasign [https://kjur.github.io/jsrsasign/](https://kjur.github.io/jsrsasign/)

opensource free pure JavaScript cryptographic library


### Supported algorithms by figo
----------------

#### Key-encryption algorithms:

* RSA-OAEP

#### Content-encryption algorithms:

* A128CBC-HS256
* A256CBC-HS512


Changelog and New Features
--------------------------

### 0.1

- Initial version


Contributing and Bug Reporting
------------------------------

Please submit bug reports and your suggestions to the GitHub [issue tracker](https://github.com/encryption_example/issues). Feel free to add pull requests as well.
