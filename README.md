Reproduce issue with special character in file name

```
$ npx webpack --mode=production src/index\?.js

Insufficient number of arguments or no entry found.
Alternatively, run 'webpack(-cli) --help' for usage info.

Hash: 60097b724a24b823ebb9
Version: webpack 4.42.0
Time: 70ms
Built at: 03/17/2020 3:00:34 PM

ERROR in Entry module not found: Error: Can't resolve '/Users/bens/git-repos/webpack-demo/src/index?.js' in '/Users/bens/git-repos/webpack-demo'
```
