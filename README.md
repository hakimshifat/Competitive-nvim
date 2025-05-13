Personal Nvim Config for Competitive Programming

You would need "cpbooster" for this. Install it using your favourite package manager.

Like "paru/yay cpbooster"

Then Install "https://github.com/searleser97/cpbooster.vim" for vim or Neovim as per your config.

After installing, execute "cpb init" to generate the config file which i mainly used to store and load my cpp template. 
And i've set an alias in my .zshrc to call this.

Make sure you have "Competitve Companion" installed on your browser.
Then Set Keybinding for compiling and running. 

Like i've set this to press F9 and run the testcases against my code.

```
vim.api.nvim_set_keymap("n", "<F9>", ":Test<CR>", { noremap = true, silent = true })
```

```

