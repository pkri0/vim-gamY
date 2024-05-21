# vim-gamY

Syntax highlighting for the GAMY programming language

## Installation

Using lazy-vim, simply copy and paste:

```
return {
    "pkri0/vim-gamY", branch = "main",
    config = function()
        vim.filetype.add({
            extension = {
                gms = "gams",
                gmy = "gams",
            },
        })
    end
}
```
