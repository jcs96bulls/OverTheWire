# Level 0-1 gtVrDuiDfck831PqWsLEZy5gyDz1clto
logged into http://natas0.natas.labs.overthewire.org and checked the page source

# Level 1-2 ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi
checked page source by using ctrl+shift+i instead of right-clicking

# Level 2-3 sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14
checked page source, checked the directory for the image source
http://natas2.natas.labs.overthewire.org/files/
checked the users.txt file

# Level 3-4 Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ
used robots.txt to find the directory with the flag

# Level 4-5 iX6IOfmpN7AYOQGPwtn3fXpbaJVJcHfq
intercepted the request with Burp Suite
In the intercepted the Get request, changed the referer to http://natas5.natas.labs.overthewire.org/index.php
The HTTP Referer header allows servers to identify where the visitors are coming from

# Level 5-6 aGoY4q2Dc6MgDq4oL4YtoKtyAg9PeHa1
intercepted the request in Burp Suite
In the Get request, changed the cookie loggedin=0 to loggedin=1
