# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
  a. Header
  b. Payload
  c. Signature
2. What information does each part contain?
  a. Header - contains two parts consisting of the type of token and the hashtag algorithm being used
    {
      "alg": "HS256",
      "typ": "JWT"
    }
  b. Payload - contains the claims which can be reserved, public, or private.
    {
      "sub": "1234567890",
      "name": "John Doe",
      "admin": true
    }
  c. Signature - You need to take the header and payload and sign these. It is used to verify that the sender of JWT is who they say they are.
3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
  JWT's are way less verbose than XML. The size is also smaller in SAML which make it extremely useful in HTTP environments. It can also use a public/private pairing key. JWT is also used at a Internet scale.
