# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?

  A JWT is comprised of a header, a payload and a signature. A JWT is key in authentication or verifying information sent between parties.

2. What information does each part contain?

  Header: type of token (JWT), hashing algorithm used

  Payload: this contains either private, reserved, or public claims or information about a specific element or user.

  Signature: The signature is comprised of 3 parts separated by periods as follows:

  header(encoded).payload(encoded)+secret.signature

3. Why do people use JWTs for authentication? A great resource to read would be

 https://jwt.io/introduction/.

 JWTs are great for authentication because their are fast, compact, and secure. They allow for a signature and have three forms of claims. Plus you  can not only use the signature to verify a user is legitimate, but you can also look at the header and payload which help create the signature. 
