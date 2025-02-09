# p8-utils
## A hobbyist set of assorted random libraries for working with the Pico 8 <br />

If you want to import any given library, make sure to clone this repo to somewhere accessible via your Pico 8 filesystem <br />

You can access the library via the `#include` keyword <br />

```lua
#include ./utils/stdio.p8
#include ./utils/strings.p8

stdout(str2bytes("hello world!\n"))
print(bytes2str(stdin()))
```
