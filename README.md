gonapps-url-query-parser
=

## About
An url query parser for lua
## Usage
**installation**
```bash
$ sudo luarocks install gonapps-url-query-parser
```
**example code**
```lua
local queryParser = require "gonapps-url-query-parser"

local parameters = {}
queryParser.parse(url, parameters)

local parameters2 = queryParser.parse(url)
```
## License
LGPLv3
