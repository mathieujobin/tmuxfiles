## Instructions

To use those files with tmux, you’d usually do:

```bash
$ cd /path/to/somewhere
$ git clone git://github.com/remiprev/tmuxfiles.git tmuxfiles-remiprev
$ ln -s /path/to/somewhere/tmuxfiles-remiprev/.tmux.conf ~/.tmux.conf
$ tmux
```

## Keyboard shortcuts

Here’s a list of keyboard shortcuts defined in `.tmux.conf`

* `<CTRL-A> <q>` Close the current pane (confirm before)
* `<CTRL-A> <s>` Split the current pane horizontally
* `<CTRL-A> <c>` Create a new window and prompt for a window name
* `<CTRL-A> <C>` Create a new window
* `<CTRL-A> <n>` Switch to the next window
* `<CTRL-A> <N>` Switch to the previous window
* `<CTRL-A> <Right>/<L>` Make the current pane 5 columns wider to its right
* `<CTRL-A> <Left>/<H>` Make the current pane 5 columns wider to its left
* `<CTRL-A> <Up>/<K>` Make the current pane 5 columns taller from the top
* `<CTRL-A> <Down>/<J>` Make the current pane 5 columns taller from the bottom
* `<CTRL-A> <,>` Rename current window
* `<CTRL-A> <.>` Move current window
* `<CTRL-A> <O>` Reload `tmux.conf`
* `<CTRL-A> <l>` Focus on the pane to the right
* `<CTRL-A> <h>` Focus on the pane to the left
* `<CTRL-A> <k>` Focus on the pane to the top
* `<CTRL-A> <j>` Focus on the pane to the bottom
* `<CTRL-A> <">` Popups the window selector dialog
* `<CTRL-A> <u>` Enter copy mode
* `<CTRL-A> <m>` Toggle monitoring for activity in current window
* `<CTRL-A> <M>` Toggle monitoring for content in current window
* `<CTRL-A> <S>` Synchronize panes
* `<CTRL-A> <Tab>` Switch to the next window
* `<CTRL-A> <z>` Extract the current panel to its own window (for easier view/copy/pasting)
* `<CTRL-A> <Z>` Restored the previously extracted panel to its original window
* `<F11>` Swap pane with the one on the left
* `<F12>` Swap pane with the one on the right
