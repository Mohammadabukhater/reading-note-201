# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS



Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

and that is clear resons to the need of the storeg space 

# Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

*ex* 
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}


f you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9).
*ex* 
if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};
PROPERTY	TYPE	DESCRIPTION
key	        string	 the named key that was added, removed, or modified
oldValue	any	     the previous value (now overwritten),or null if a new item added
newValue	any	    the new value, or null if an item was removed
url*	    string	the page which called a method that triggered this change