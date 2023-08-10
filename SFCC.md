```

IOT write to server logs:
javascript
var Logger = require('dw/system/Logger');

// Create a logger instance
var logger = Logger.getLogger("MyLogger");

// Log a message at the desired log level
logger.debug("This is a debug message");
logger.info("This is an info message");
logger.warn("This is a warning message");
logger.error("This is an error message");
```
