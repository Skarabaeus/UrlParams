###  URL Params

## LICENSE:

MIT-LICENSE:http://www.opensource.org/licenses/mit-license.php

## USAGE:

    $.urlParmas("get", "param_name") // => returns unescaped string of the parameter "param_name"
    $.urlParams("keys") // => returns an array of all parameter keys
    $.urlParams("exists", "param_name") // => returns true if "param_name" exists; false otherwise
    $.urlParams("all") // => returns a hash with all key, value pairs