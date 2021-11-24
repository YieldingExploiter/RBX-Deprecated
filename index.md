# RBX-Deprecated
This repository contains a shortcut to deprecated methods in Roblox.

This is by no means a complete list, and may include things for other projects.

## Usage
To use this within your own code, add the following:
```lua
local depWarn = (function()local v = false;local function pad(str,int,chr)repeat str=chr..str until #str >= int;return str;end;local function d(i)i=pad(tostring(i),3,'0');warn('[D'..i..'] This method is deprecated! See https://yieldingexploiter.github.io/RBX-Deprecated/D'..i..' for more information.');if v == false then print('A list of deprecated functions found here (and what to use instead), can be found here: https://github.com/YieldingExploiter/RBX-Deprecated');v=true;end;end;end)();
```
to your script, then call `depWarn(4)` to tell the user to see [D004](https://yieldingexploiter.github.io/RBX-Deprecated/D004).

## Contributing
You can contribute by making a [Pull Request](https://github.com/YieldingExploiter/RBX-Deprecated/pulls)! It doesn't matter if your PR contains Roblox-related Deprecations, or ones related to your own library/libraries! Just file a Pull Request, and it will likely be added.

## List
<!-- Auto-Generated Code -->
%INSERT_LIST%
