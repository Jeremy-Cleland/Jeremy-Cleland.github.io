# Class 15 Reading Notes | Authentication

## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

## Discussion Questions

- Q: What is OAuth?

  - A: OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

- Q: Give an example of what using OAuth would look like.

  - A: Auth allows websites and services to share assets among users. The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

- Q: How does OAuth work? What are the steps that it takes to authenticate the user?

  - A:

  1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

  2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

  3. The first site gives this token and secret to the initiating user’s client software.

  4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

  5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

  6. The user approves (or their software silently approves) a particular transaction type at the first website.

  7. The user is given an approved access token (notice it’s no longer a request token).

  8. The user gives the approved access token to the first website.

  9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

  10. The second website lets the first website access their site on behalf of the user.

  11. The user sees a successfully completed transaction occurring.

  12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

- Q: What is OpenID?

  - A: OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans

## [Authorization and Authentication flows](https://auth0.com/docs/flows)

## Discussion Questions

- Q: What is the difference between authorization and authentication?

  - A: Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.

- Q: What is Authorization Code Flow?

  - A: The authorization code grant type is used to obtain both access tokens and refresh tokens and is optimized for confidential clients. Since this is a redirection-based flow, the client must be capable of interacting with the resource owner's user-agent (typically a web browser) and capable of receiving incoming requests (via redirection) from the authorization server.

- Q: What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

  - A: The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier.

- Q: What is Implicit Flow with Form Post?

  - A: Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

- Q: What is Client Credentials Flow?

  - A: The client can request an access token using only its client credentials (or other supported means of authentication) when the client is requesting access to the protected resources under control, or those of another resource owner that have been previously arranged with the authorization server (the method of which is beyond the scope of this specification).

- Q: What is Device Authorization Flow?

  - A: The Device Authorization Flow contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser. The browser flow path, wherein a device code is bound to the session in the browser, occurs in parallel to part of the device flow path.

- Q: What is Resource Owner Password Flow?

  - A: The resource owner password credentials grant type is suitable in cases where the resource owner has a trust relationship with the client, such as the device operating system or a highly privileged application. The authorization server should take special care when nabling this grant type and only allow it when other flows are not viable.

## Things I want to know more about
