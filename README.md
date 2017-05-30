# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials are how a user proves they are who they say they are.

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Cookies are small strings that can total 4K per website. They are sent in headers by both client and server. They are set by the server and sent to the client. The client can then return the cookies to authenticate and authorize them on that website.

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

A strength is that they exist only between a client and a specific website. Another website can't read your cookies, nor can a client access cookies of another client.

A weakness is that if cookies are setup improperly setup, malicious javascript could read them and then they could be used for authentication spoofing. Another weakness is that users can disable them or delete them, so they shouldn't be relied on too heavily.

> What is the difference between a session cookie and a persistant cookie?

Cookies can have their duration defined, called persistant cookies. Session cookies get deleted when the browser is closed.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

Same origin policy can make it more difficult to develop, but it has good security benefits. It makes it more difficult for someone to make resource calls from third party sites.

> Based on what you know, how would you explain CORS?

CORS makes it possible for someone on site A to make a call and get resources from site B and have those resources display on the client.
