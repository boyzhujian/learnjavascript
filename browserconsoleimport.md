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
var jq = document.createElement('script');
jq.src = "http://underscorejs.org/underscore.js";
document.getElementsByTagName('head')[0].appendChild(jq);

```
