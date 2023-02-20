# Class 6 Reading Notes | Authentication

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

- Q: Explain to a non-technical friend how you would safely hash and store a password.

  - A: Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password. I would diccuss the different algorithms which provid the besk protetion. 

- Q: What is Bcrypt?

  - A: Its an algorithm used to overcome brute force attacks. Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

- Q: Why might you use something like Bcrypt?

  - A: You would want to use Bcrypt to mitigate the risks of brute Force and hash collision attacks

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

- Q: What is Basic Authentication?

  - A: Basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

- Q: What properties are necessary in the header of a Basic Auth request?

  - A: Authorization: Basic `<credentials>`

- Q: How are `username:password` in Basic Auth encoded?

  - A:  Base64 encoding of ID and password joined by a single colon :

## [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

- Q: Define the authentication process for a non-technical recruiter.

  - A: Authentication is the process of verifying that an individual, entity or website is who it claims to be.

- Q: How should your error messaging respond (both HTTP and HTML)? Why?

  - A: Vague and generic error message prevent providing information to potential hackers.

- Q: Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

  - A: [Authentication Cheat Sheet¶]( https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

    
## Things I want to know more about

Functional React Components and HOOKS!