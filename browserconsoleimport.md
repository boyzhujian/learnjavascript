### load jquery script 
```
var jq = document.createElement('script');
jq.src = "https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js";
document.getElementsByTagName('head')[0].appendChild(jq);
// ... give time for script to load, then type (or see below for non wait option)
jQuery.noConflict();
```


### underscore
```
var ud = document.createElement('script');
ud.src = "http://underscorejs.org/underscore.js";
document.getElementsByTagName('head')[0].appendChild(ud);

```


### moment
```
var moment = document.createElement('script');
moment.src = "https://momentjs.com/downloads/moment.js";
document.getElementsByTagName('head')[0].appendChild(moment);

```

