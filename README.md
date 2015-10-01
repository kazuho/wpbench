# wpbench - collect the load timings of a web page

Web-site performance is a crucial factor to succeeding in the Web business.
According to [a research conducted by Microsoft](http://radar.oreilly.com/2009/07/velocity-making-your-site-fast.html), 500msec slowdown in Bing causes their revenue go down by 1.2%.

Wpbench collects the following metrics required for tuning the performance.
The primary goal of performance tuning will be to minimize _first-paint_ time, so that the visitors to the web site can start working on the destination page as early as possible, and the second goal will be the _load_ time.

Event | Description 
----- | -----------
unload | timing when the browser switches to the destination page; the new page will be blank until
first-paint | timing when some content of the destination page is rendered by the web browser
load | timing when all the downloads are complete

It is known to work with: Chrome, Firefox, Safari.

How-to
------

1. upload _wpbench.html_ to your web-site
1. open the uploaded HTML
1. enter the path of the web-page you want to take the benchmark
1. hit the _start_ button
