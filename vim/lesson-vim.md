# Lessons

## VIM

### Configurations

- customizing vim
- importance of init config file for nvim `~/.config/nvim/init.vim`
- importance of good typing skills
- doing proper documentation for config settings while writing config files
- explain the role of leader key [default is `\`]
- basic vim command settings in `init.vim` file
- neovim configuration file path and files names (vim = `.vimrc` nvim = `init.vim`)
- saving the vim `init.vim` config file with `init.vim.save` backup file
- emailing config files of vim `.vimrc` and `~/.config/nvim/init.vim` using gmail

### Plugins Installations

- neovim Plug configuration (`nvim-plug`)
- neovim Plug install and clean (autoremove) commands
  - `:PlugInstall`
  - `:PlugClean`
  - `:PlugStatus`
  - `:PlugUpdate`
  - `:PlugUpgrade`
- basic theme plugin (`github-nvim-theme`, `tender` theme, `dracula` theme)
- basic statusbar plugin (`lightline` statusbar theme)
- basic navigation tree plugin (`nerdtree`)
- error handling during plugin installations

### vim-plug

- link to github repository [vim-plug](https://github.com/junegunn/vim-plug)
- read `readme.md` file and do installations as instructed

### NerdTree plugin

- basic navigation of neredtree using commands [`C-t`, `C-n`, `C-o`, `Leader-n`]
- Use `?` to show help while focus on NerdTree . Press again `?` to hide.
- Use `t` to open file as new tab.
- link to github repository

### Key Bindings

- mapping keys (for `:tabnew` mapping using `C-arrow-keys`)
- for Key Bindings
  ```
	<S-...>  shift-key                      shift <S-
	<C-...>  control-key                    control ctrl <C-
	<M-...>  alt-key or meta-key            meta alt <M-
	<A-...>  same as <M-...>                <A-
	<D-...>  command-key (Macintosh only)   <D-
   ```
- use `help: key-notations`

### New Tabs using `:tabnew`

- using `:tabnew` and navigation between tabs using [`gt` and `gT` and `1gt` and `2gt`]
- using `:tabn` for next tab and `:tabp` for previous tab. `exit` or `q` to close tab.

### Navigation in vim

- vim command `gg` and `G`
- vim command `dgg` and `dG` effective use
- vim usage of command `gg` and `G` effectively
- using `h`, `j`, `k`, `l` keys
- `C-u`, `C-d`, `C-e` and `C-y` key navigation
- Using `H` for top height `M` for middle `L` for lowest height navigation for cursor movement
- navigate with word `e` and `w`
- use with change `cw`, `ce`, `ciw`, `caw` and use with delete `d` and yank `y`

### using edit and buffers

- vim command `:buffer` or `:b filename.text`
- vim command to open file for edit `:edit file1.txt` or `:e file1.txt`

### Case Commands

- lower/upper case using `~`
- vim uppercase/lowercase switching of words and characters

### Vim modes

- vim visual mode with `v` 
- vim visual line mode with `V`
- vim Visual Block mode with `C-v`

### Vim command history

- enter into command mode by `:`
- for history navigation type `:` followed by `up` or `down` arrow key
- for vim history `window` type `:` followed by `C-f` to open previous command history
- scroll through `history window` of vim and select with arrow navigation followed by enter
- `k` and `j` keys can be used for navigation as well
- to close `:q` to quite vim history window
- to close `C-c` followed by again `C-c` or `esc` key
