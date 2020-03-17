# Issue With Question Mark Character (`?`) in File Name

Instructions and my environment

## Reproduce

```
$ npx webpack --mode=production src/index\?.js

Insufficient number of arguments or no entry found.
Alternatively, run 'webpack(-cli) --help' for usage info.

Hash: 60097b724a24b823ebb9
Version: webpack 4.42.0
Time: 70ms
Built at: 03/17/2020 3:00:34 PM

ERROR in Entry module not found: Error: Can't resolve '<personal path>/webpack-demo/src/index?.js' in '<personal path>/webpack-demo'
```

## My Environment

```
system_profiler SPSoftwareDataType
Software:

    System Software Overview:

      System Version: macOS 10.15.3 (19D76)
      Kernel Version: Darwin 19.3.0
      ...
```

```
$ node --version && npm --version
v10.14.2
6.13.6
```
