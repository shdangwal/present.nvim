# `present.nvim`

Hey, this is a plugin for presenting markdown files!!

# Features: Neovim Lua

Can execute code in lua blocks, when you have them in a slide

```lua
print("Hello world", 37)
```

# Features: Other langs

Can execute code in Language blocks, when you have them in a slide
You may need to configure this with `opts.executors`, only have Python and Javascript by default

```javascript
console.log("Hello world of javascript")
```


# Features: Python

Can execute code in python blocks, when you have them in a slide

```python
print("Hello world of python")
```

# Usage
```lua
require("present").start_presenation {}
```

Use `n` and `p` to move between slides and `q` to close window.

Or use `PresentStart` command

# Credits

shdangwal
