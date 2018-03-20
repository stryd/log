log
=======
Go logging library used at Stryd.

Usage
-------

The Stryd/log package supports following basic logging features:

1. Multi level logging with different color
2. Log file writing
3. Log file rotating

Update
-------
This library is only used in the development phase of projects. Once the
project is mature enough to go to product env, we use [Stackdriver logging
library](https://github.com/stryd/cloudlog) to aggregate logs to Google Cloud console.
