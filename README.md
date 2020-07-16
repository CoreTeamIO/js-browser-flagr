### jsFlagr Browser Port

jsFlagr is the client for Checkr Flager Project.
Flagr is an open source feature flag software.
It comes with a server and uses swagger to generate the clients.

However since it's js module is an NPM Module, it's not easy to use via &lt;script&gt; tag in the browser.
I've created a simple port, using browserify and included an example to get you started quickly.

* Flagr Project: https://checkr.github.io/flagr/
* Flagr GitHub: https://github.com/checkr/flagr
* Flagr Docs: https://checkr.github.io/flagr/#/home
* jsFlagr Project: https://github.com/checkr/jsflagr




#### How to Use
1) run `npm install`
2) run `npm run build`
3) open `test.html` to see how to use
4) include `dist/jsflagr.js` or self host and include in your html
5) Use as part of Flagr.
 
