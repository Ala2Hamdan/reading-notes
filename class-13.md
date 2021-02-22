# the Past, Present, and Future of Local Storage for Web Applications
* persistent local storage is one of the areas where native client applications have held an advantage over web applications.
* Cookies have three potentially dealbreaking:
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application, but not enough to be terribly useful
* HTML5 Storage :it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.
* From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.
* TRACKING CHANGES TO THE HTML5 STORAGE AREA:
`setIذtem()`, `removeItem()`, `clear()`
