v0.4.4:
- Compile ACVP parser tool with -m32 for 32 bit testing
- Fix DSA siggen helper to generate PQG and DSA key at the same time
- constify data in parser_common.c

v0.4.3
- OpenSSL: enable SHA3/HMAC SHA3

Changes 0.4.2
- add helper convert_cipher_algo
- use specific initializations for static variables (some compilers cannot handle generic initializations)
- statically link JSON-C

Changes 0.4.1
 * Addition of helper function to turn an MPI into a byte array

Changes 0.4.0
 * First public release with support for ACVP v0.5