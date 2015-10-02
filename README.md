# wpbench - collect the load timings of a web page

Web-site performance is a crucial factor to succeeding in the Web business.
According to [a research conducted by Microsoft](http://radar.oreilly.com/2009/07/velocity-making-your-site-fast.html), 500msec slowdown in Bing causes their revenue go down by 1.2%.

Wpbench collects the following metrics required for tuning the performance.
The primary goal of performance tuning will be to provide _some_ visible response to user so that they can start working on, and the second goal will be the _load_ time.

Event | Description 
----- | -----------
unload | timing when the browser switches to the destination page (which will be blank at this moment)
parsed &lt;head&gt; | when parsing of &lt;head&gt; completes (indicates that all scripts in head have been loaded)
loaded CSS in &lt;head&gt; | when all the stylesheets in &lt;head&gt; have been loaded; this is essentially when the browser becomes capable of rendering something
DOMContentLoaded | timing when the entier HTML is laid out
load | timing when all the downloads are complete

It is known to work with: Chrome, Firefox, Safari.

How-to
------

1. upload _wpbench.html_ to your web-site
1. open the uploaded HTML
1. enter the path of the web-page you want to take the benchmark
1. hit the _start_ button
