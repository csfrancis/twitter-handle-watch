# Twitter Handle Watch

A small script that can be used to monitor Twitter and notify via email when a handle becomes available.

## Configuring

See [config.example.json](https://github.com/csfrancis/twitter-handle-watch/blob/master/config.example.json) for a configuration template.

The script will look for a config file named `~/.thwatch.config.json`. The config file can be overridden by passing the the `-c` parameter to the script:
```
./thwatch -c config.json
```

## Running

```
./thwatch
```

The only output generated is when a notification email is sent. Any error output will be output to standard error.
