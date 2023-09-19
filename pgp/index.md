# Ledger of PGP Keys
In here you will find my public key infrastructure.

**Quick Reference:**
[[Root Key](https://bytz.zip/pgp/bytz.pgp)]

[[Latest Monthly Key](https://bytz.zip/pgp/bytz-19-10-2023.pgp)]

There's a few concepts at play here, let me help you understand my system.

**Root** - This is my root identity key. This key should never change, and all other keys in here are certified by it.

**Monthly** - These are my rotating monthly keys. They will be listed with their expiration, and their revocation certificates. When a revocation certificate is added, it means I've moved on to next month's key.

**Special Use** - For all other keys I may need to issue. :)

### Bytz! I need to encrypt something for you!
Use my Root public key. 
If you encrypt something with my monthly keys, it will likely be ignored.

## Root Key
[./bytz.pgp](https://bytz.zip/pgp/bytz.pgp)

This is my Root public key. This key should almost never be used for signing anything.

## Monthly Keys
**19/09/2023 - 19/10/2023**

[./bytz-19-10-2023.pgp](https://bytz.zip/pgp/bytz-19-10-2023.pgp)