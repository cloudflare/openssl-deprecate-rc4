openssl-deprecate-rc4
=====================

Small patch for OpenSSL that deprecates the use of RC4 if the TLS
version is greater than 1.0.

See http://blog.cloudflare.com/killing-rc4 for more details.
