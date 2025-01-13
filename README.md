# _ga_measuremnet_id_cookie_reader

Each GA4 property attached to a web page will drop a cookie named "_ga_[measurement_id]", in addition to the standard _ga cookie.

This cookie contains useful information, such as session count. This script reads and dissects the _ga_&lt;measurement_id> cookie value and returns a parsedCookies array.

This array contains the following properties:

* Measurement IDs
* Version
* Domain Level
* Session Start At
* Sessions Count
* Engaged Session
* Last Event At
* Engaged Time
* Countdown
* Mystery Zero 1
* Mystery Zero 2
* Duplicate Stream

The script can be run in the browser console for initial testing.

