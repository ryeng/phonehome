phonehome
=========

A snap that phones home by sending periodic HTTP GET requests to any URL.


Configuration
-------------

```
snap set url=http://example.com/script frequency=1m
```

The frequency is specified in the same format as the sleep command, a
number and a unit suffix. Use "s" for seconds, "m" for minutes, "h"
for hours, or "d" for days. If no suffix is specified, the value is
interpreted as seconds.

The default frequency is once per minute.
