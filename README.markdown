# Rename.vim

A github mirror of Rename.vim by Christian J. Robinson. See http://www.vim.org/scripts/script.php?script_id=1928

## Tips & Tricks:

This keybinding will automatically populate the command prompt with the current filename in case you only wanted to, for example, change only one character in the filename without having to retype it all:

```
nmap <Space>r :call feedkeys(":Rename " . expand('%@'))<CR>
```

Credits: @geneotech
