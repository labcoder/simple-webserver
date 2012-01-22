<html>
<h1>Simple webserver</h1>
<p>This example of a simple webserver is inspired by IBM's really small webserver example, nweb.</p>
<hr>
<h2>Uses</h2>
<p>This is obviously not meant to be used for real deployment, and is just out here in case someone wants to see a small c-based webserver in use. Basic socket use examples are in here from nweb. Also included are two small pages to serve up.</p>
<hr>
<h2>Example</h2>
<p>Run the Makefile</p>
<pre>make</pre>
<p>You run the server like this:</p>
<pre>./server [port] [location to serve pages from] [& - to run in background]</pre>
<p>For example, to run it on port 8080, you'd do something like this:</p>
<pre>./server 8080 ./ &</pre>
</html>
