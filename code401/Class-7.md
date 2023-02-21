# Class 7 Reading Notes | Access Control (ACL)

## [Intro to JWT](https://jwt.io/introduction/)

- Q: What is a JSON Web Token (JWT)?

  - A: JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
  [^](https://jwt.io/introduction/)

- Q: When should we use JSON Web Tokens?

  - A: Authorization & Informational Exchange

- Q: Claims are expected in which structural component of a JWT?

  - A: Payload

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

- Q: If I get a JWT and I can decode the payload, how can we call that secure?

  - A: Once we receive a JWT, the verification will take its header and payload, and together with the secret that is still saved on the server create a test signature and compare it to original signature to ensure nothing has been tampered with.

- Q: If sending a JWT, what must the sender and receiver both know? Hint, it’s appended in the signature.

  - A: Hash(payload + secret)

- Q: Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

  - A: When sending a JWT to someone it takes the content + secret and uses a hash function which gives a long string of characters and if anything about the content or secret is changed it wont pass the test. JWT doesn't work solely alone but is an additional layer which has a very specific task. 

## [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

- Q: Why use JWT?

  - A:

- Q: JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

  - A: JWT is so compact you can send it via URL and send it with simple requests like submitting forms or loading content. The sever also doesn't know which users are logged in, but only verifies that the token they have is valid. 

- Q: What are the three components (the structure) of a JWT signature?

  - A: 
    - Header
    - Payload
    - Signature

    
## Things I want to know more about
