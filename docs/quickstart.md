# Quickstart
```python
import zazzle

# This only needs to be run once, and should be passed any
# configuration parameters you need for your logger.
zazzle.configure_logger()

# zazzle.log(log_level(int), log_message(string))
zazzle.log(1, "Hello world!")
```

This two-liner will produce a log in the following directory with the current date as the file name. The log will contain a single 'INFO' level log message. Levels 0-4 can be used here.

```bash
"C:\Users\'current user'\Documents\Zazzle\Y-M-D.log"
```

```bash
| INFO     |    Hello world!
```