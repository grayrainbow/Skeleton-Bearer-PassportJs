# Skeleton-Bearer-PassportJs
 Skeleton app running on NodeJS, built with Express4 using the Bearer Passport authentication mechanism

<br />OAuth 2 is an authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Facebook, GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account. OAuth 2 provides authorization flows for web and desktop applications, and mobile devices.  (ref.: https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2 )
<br/>
<h3>To install :</h3>

<ul><li>1) Make sure you have NodeJS LTS and MongoDB installed :)</li>
<li>2) <code>git clone https://github.com/grayrainbow/Skeleton-Bearer-PassportJs</code></li>
<li>3) <code>npm install</code></li>
<li>5) <code>set DEBUG=myapp:* | npm start</code></li>
<li>6) Browse to <a href="http://localhost:3000">http://localhost:3000</a></li>

</ul>

<p>For testing, in a terminal, do : </p>
<code>curl -v http://127.0.0.1:3000/authenticate/?access_token=123456789</code><br/>
<code>curl -v http://127.0.0.1:3000/?access_token=123456789</code>

