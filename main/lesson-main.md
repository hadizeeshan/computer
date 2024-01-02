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

## Tmux Terminal

- commands for tmux
- command `tmux ls`
- command `tmux new -s session-name` or `tmux new-session -s session-name`
- detach/close tmux session [`C-b d`]
- command `tmux attach -t main` or `tmux a -t main`. `-t` is for target window.
- `exit` closes the tmux window
- rename tmux window [`C-b ,`]
- create new tmux window [`C-b c`]
- switch between tmux windows [`C-b 0`, `C-b 1` ... ]
- switch beteen tmux windows using next `n` and previous `p` windows [`C-b n`, `C-b p`]
- close tmux session command [`tmux kill-session -t 0` or `tmux kill-session -t main`]
- command `tmux kill-session` will kill all active running sessions
- rename session usage `rename-session -t target-session new-name`. 
- rename session inside tmux, use [`C-b $`] to rename session.
- command to split vertical window as pane using [`C-b %`]
- command to split horizonatal window using [`C-b "`]
- `exit` command closes split window [`C-b "`]
- navigating between split panes using [`C-b arrow keys`]
- resize split panes using [`C-b C-arrow keys`]
- use [`C-b [`) to go to editing mode to scroll up and down using arrow keys. `q` to exit
- use [`C-b w`] to show all windows and select accordingly. Use `esc` to exit selection.

## Markdown 

- Markdown language
- Markdown preview plugin using vim
- Markdown preview shortcut
- link to github [markdown-preview](https://github.com/iamcco/markdown-preview.nvim)

## GitHub

- Github account signin/signup
- integrate ssh-key with github account
- installl git 
- git command start with `git init`
- git commad to add files with `git add README.md` `git add .` to add all files
- git command to commit files with `git commit -m "Added: New files."`
- git command to change master to main `git branch -m master main`. Use after commit.
- git command to push files with `git push -u origin master` or `git push -u origin main`
- git command to pull files from github `git pull origin master`
- git command to add remote `git remote add origin git@github.com:hadizeeshan/hadi.git`
- change main branch name from `master` to `main` from github or vice-versa
- git command to clone using `git clone url`
- 

## SSH keygen

- create ssh-key using
- backup ssh-key files
- install ssh `sudo apt install ssh`
- check help with `service ssh help` which will show usage
- start service with `sudo service ssh start`
- check if ssh is running with `service ssh status`
