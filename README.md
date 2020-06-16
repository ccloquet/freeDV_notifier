# freeDV_notifier
Receive a push notification when there is activity on the freeDV QSO finder - quick and dirty serverless/client-based script

Based upon the work of K7VE's [QSO Finder](http://qso.freedv.org) for [freeDV](https://freedv.org).

1. create an account on pushover.net, register a device and create an API key
2. update the script in index.html with your pushover credentials (user name and application API key)
3. load it in your browser and wait. You should receive a notification when a new comment is posted in free. 

Notes:
 - you might need to reload the page if you exit the browser. 
 - only use it locally. *Do not* put it on a server as it contains your credentials

TODO: add filters (eg: only receive the connect events, or the QSY on certain bands), add a server part to subscribe without the need to run it in your browser, ...

