# Security

## Auth
what is authentication?
  - A process where credentials provided are compared to ones in a database.
what is authorization?
  - Grants certain permissions based on authentication.

## Hashes

What is a hash?
  - The transformation of a string of characters into a fixed-length value or key that represents the original string.
Why should we hash our passwords?
  - It encrypts our passwords using a one way transformation of the inputed password to the hashed password. It makes our passwords pretty much unreadable if our database is breached.
What is a salt?
  - It is a random string of data that is used to modify the hash.
Why should we use salts?
  - It makes our hashes more secure by adding random strings to them.
Why should we use slow hash algorithms and not fast ones?
  - Using slow hash algorithms slows down the process of converting a string into a hashed encrypted string. It aims to delay hackers.

## Cookies

What is a cookie? (key value pair that gets stored by the browser)
  - A cookie is a small piece of data (4kb max) sent from a website and stored in the user's web browser while the user has the browser open, or until the cookies expire.
What are the two types of cookies and how do they differ? (session / persistent)
  - A session cookie, also known as an in-memory cookie or transient cookie, exists only in temporary memory while the user navigates the website.
  - Instead of expiring when the web browser is closed as session cookies do, a persistent cookie expires at a specific date or after a specific length of time.
View your coursework.galvanize.com cookie. cmd+opt+i -> resources -> cookies

## Sessions

What is a session?
  - Simalir to a cookie, but the data is stored on the server instead of the client.
Are sessions different than cookies?
  - Yes cookies store information in the client, but sessions store the data in the server.
