When you have a secret in the MacOS keychain, in the "login" default keychain, with the following attributes:

Kind: application password
Account: username@example.com

How to access a secret in Mac OS keychain from a shell script:

security find-generic-password -a username@example.com -w
