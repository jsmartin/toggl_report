#toggl_report


This tool uses the [Toggl Reports API](https://github.com/toggl/toggl_api_docs/blob/master/reports.md) to generate a status report that is broken down by User->Client->Project->Tasks.

It currently spits out the report in markdown to stdout.

A sample can[ be seen here.](sample.md)


```
usage: toggl_report [-h] start end

positional arguments:
  start       The start date in YYYY-MM-DD format
  end         The end date in YYYY-MM-DD format

optional arguments:
  -h, --help  show this help message and exit
```

## Requirements

### Python
Python 2.7

### Modules
more_itertools

### Toggl API Key

You must get your Toggl API key from your Toggl Profile and set it as a environment variable.

```export TOGGL_AUTH_KEY="jalskdjflkasdjflkjlkej2lk3j23lkj"```