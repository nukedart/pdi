+++
title = "Getting Started with Python"
image = "/images/post/post-2.jpg"
author = "Pete Dziedzic"
date = 2019-11-07T05:00:00Z
description = "This is meta description"
categories = ["Security","Python","Programming"]
type = "post"
+++

Before we begin, please note we will be starting from complete scratch. The first step

Make sure you have the path in your file with:
```
#!/usr/bin/env python
```



Let add some code to our file in order to demonstrate some code execution

```
#!/usr/bin/env python

import datetime
 
currentDT = datetime.datetime.now()
 
print ("Current Year is: %d" % currentDT.year)
print ("Current Month is: %d" % currentDT.month)
print ("Current Day is: %d" % currentDT.day)
print ("Current Hour is: %d" % currentDT.hour)
print ("Current Minute is: %d" % currentDT.minute)
print ("Current Second is: %d" % currentDT.second)
print ("Current Microsecond is: %d" % currentDT.microsecond)
```

Make the file an executable with:
```
chmod +x myfile.py
```

Run / Execute with:
```
./myfile.py
```

