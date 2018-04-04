# PasswordEncryptDecrypt
Aplication to create salt to protect password.

## Methods
- hash(String password, byte[] salt) -> return the hashed password with a pinch of salt

Returns a salted and hashed password using the provided hash. The password is destroyed (the char[] is filled with zeros)

- getNextSalt() -> return a 16 bytes random salt

Returns a random salt to be used to hash a password.

- isExpectedPassword(String password, byte[] salt, byte[] expectedHash) -> return true if the given password and salt match the hashed value, false otherwise.

Returns true if the given password and salt match the hashed value, false otherwise. The password is destroyed (the char[] is filled with zeros.
     
     
     
