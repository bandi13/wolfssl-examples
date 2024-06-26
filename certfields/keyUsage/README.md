An app for checking the keyUsage Extensions in a cert.

Assumptions:
wolfSSL Library must be configured with --enable-opensslextra
wolfSSL lib installed to /usr/local

NOTE: If wolfSSL is installed to custom directory edit Makefile variable
      WOLFSSL_INSTALL_DIR accordingly for example if you configured wolfSSL with
      "--enable-prefix=/home/me/wolf-install-dir" then set WOLFSSL_INSTALL_DIR to
      "/home/me/wolf-install-dir" before running "make"

Building:
make

Cleaning:
make clean

Sample output:

```
keyUsage % ./run
cert can be used for CERTIFICATE SIGNING
cert can be used for CRL SIGNING
```

If there are any questions please do not hesitate to reach out to wolfSSL
support staff via support [at] wolfssl [dot] com or through the zendesk channel
at https://wolfssl [dot] zendesk [dot] com anytime.
