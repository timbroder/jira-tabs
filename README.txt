Add this as a bookmarklet to your browser:
[JiraTabs](javascript: function tab(a){"use strict";var b=document.getElementById(a).getElementsByTagName("tr"),c=window.confirm("Do you want to open "+(b.length-1)+" Jiras?");if(c)for(var d=1;d<b.length;d++){var e=b[d].getElementsByClassName("summary")[0].getElementsByTagName("a")[0];window.open(e.href)}}tab("issuetable"))

Whenever you are in the filter view of jira, click the button and all the visible jira's will open in new tabs.
