
1. Simulate encryption communication, encrypt a message use an RSA public
key, and try to decrypt it with an RSA private key.
2. Try to crack a private key with a known public key. And determine the
key component to keep the security of RSA encryption communication.
Hint: the key is find out d, we can get private key once we have d. Is it
possible to derive d in the case of n and e?
1. ed (mod φ(n)) = 1
2. φ(n) = (p-1)(q-1)
3. n=pq
