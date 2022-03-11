# log-generator

## General info
The source code is clone from https://github.com/vspiewak/log-generator and is modify for use in JDK 11+.

## How to run the program
To generator random log record every 5 seconds:

java -jar log-generator-\<version\>.jar -n 1 -r 5000
```
  Options:
        --help

       Default: false
  * -logs, -n
       Number of logs to generate
    -repeat, -r
       Repeat every N milliseconds
       Default: 0
    -threads, -t
       Number of threads to use
       Default: 1
```
## Docker
Have fun with testing custom pipeline for log monitoring using Datadog agent
