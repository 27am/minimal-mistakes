---
layout: posts
title:  "Python logging"
categories: personal
---

To act as a reference for every program

```
import logging

'''
- DEBUG (lowest)
- INFO
- WARNING
- ERROR
- CRITICAL (highest)
'''

# get the logger
logger = logging.getLogger()

# set parameters
handler = logging.FileHandler("file.log")
formatter = logging.Formatter('%(asctime)-8s %(levelname)-8s %(message)s')

# add parameters
handler.setFormatter(formatter)
logger.addHandler(handler)
logger.setLevel(logging.DEBUG)

logger.debug("something worth of logging")
```

For a deeper dive, visit [here](https://docs.python.org/3/howto/logging.html#logging-basic-tutorial)
