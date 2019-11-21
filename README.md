# pm2-syslogx [![NPM version][npm-image]][npm-url]  [![Code Style: Google](https://img.shields.io/badge/code%20style-google-blueviolet.svg)](https://github.com/google/gts)

## Installation
```bash
pm2 install pm2-syslogx
```

## Configuration
This module is bundled with the following default configuration
```javascript
      {
        "host": "localhost", // syslog server hostname
        "facility": "user", // syslog facility
        "logLevel" : "info", // syslog supported log level
        "port" : 514, // syslog port
        "json" : false, // output log as a JSON
        "skipPM2" : false, // toggle pm2 core service logs
        "apps": ["all"] // apps to log
      }
````
In order to update a property, please use the following syntax
```bash
pm2 set pm2-syslogx:<attr> <val>
```

## Uninstall
In order to uninstall the module, please use the following command
```bash
pm2 uninstall pm2-syslogx
```

## License

MIT © [fourthofaugust](https://github.com/fourthofaugust)


[npm-image]: https://badge.fury.io/js/generator-udutha.svg
[npm-url]: https://npmjs.org/package/generator-udutha
