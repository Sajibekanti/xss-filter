# xss-filter
In index.html when you enter xss payload such as "><img src=x onerror=prompt(1)>" then it moves to php file where this payload get's filtered because of htmlspecialchars() php function.

Using php function designed a small code which eliminates xss (99%) , we can't say 100% there may be some bypass to this as well.
Google security engineer http://blog.kotowicz.net/ explains the bypass in his blog.
So we need to be carefull about it...
