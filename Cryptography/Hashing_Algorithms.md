 - MD5

MD5 generates a 128-bit hash that is very useful for non cryptographic functions.
It is primarally used for generating checksums, as it is very easy to crack the encryption.
It is faster than other hashing algorithms for the purpose of hashing because it is faster.
However the speed is a result of the hash only being 128-bit, much larger values are more secure but slower.

 - SHA

SHA is a hashing algorithm initially based on a modified version of MD5.
There are multiple versions of SHA, each one moving farther and farther away from MD5
It is considered to be a lot more secure than MD5, making it much harder to crack.
SHA3 can output a hash size as big as 512-bit. 

- bcrypt

bcrypt is a password-hasing algorithm, the goal of hash is to prevent anyone from easily brute forcing a password.
The algorithm uses a technique called salting to prevent the use of rainbow table attacks.
Additional data is added to a password so the hash value is very different from what the password hash would normally look like.
