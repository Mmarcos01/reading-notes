[Home](README.md)

## Local Storage :

[Local Storage](http://diveinto.html5doctor.com/storage.html)

Downsides of using cookies for local storage:  

- Slows down your web app by needlessly and continuously transmitting the same data over again
- Unencrypted data
- Cookies are limited to around 4kb of data

HTML5 Storage is a way for web pages to store named key/value pairs locally within the browser. Data persists even after leaving the website and closing the browser. Unlike cookies, the data is never transmitted to the remote web server unless manually intended.  

HTML5 Storage is based on key/value pairs. You store data based on a named key, then retrieve that data with the same key. The data can be any type supported by JavaScript, however, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt().

From your JavaScript code, you access HTML5 storage through the localStorage object on the global window object.  

### Check for HTML5 Storage:

function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}  

You can also use Modernizr to detect support for HTML5 Storage:  

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}

[Home](README.md)