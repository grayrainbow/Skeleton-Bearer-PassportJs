# Skeleton-Bearer-PassportJs
 Skeleton of a Node.JS/ExpressJs 4 RestAPI using the Bearer Passport authentication mechanism.  
 The app / client require an API key (see models) to access the ressources.

<br />Suggestion : use it with PassportJS Oauth2
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

