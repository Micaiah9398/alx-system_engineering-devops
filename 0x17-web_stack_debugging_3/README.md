######A Quick and Easy Guide to tmux

Over the years I’ve tried to streamline and customize my command line experience to be more convenient, more fun to use or just to look rad. One of the most important tools to drive my daily command line experience is tmux. Check this out:

tmux in action

This screenshot shows nothing less than the best thing since sliced bread. It’s tmux, a so-called terminal multiplexer. Simply speaking, tmux acts as a window manager within your terminal1 and allows you to create multiple windows and panes within a single terminal window.

This post will give you the same quick introduction to tmux and its possibilities, followed by the a 10 minute hands-on guide to set up and get to know tmux yourself. If you’ve got 10 minutes to spare and want to earn street cred with your nerd friends: read on and become proficient with tmux!

What’s tmux?
tmux’s authors describe it as a terminal multiplexer. Behind this fancy term hides a simple concept: Within one terminal window you can open multiple windows and split-views (called “panes” in tmux lingo). Each pane will contain its own, independently running shell instance (bash, zsh, whatever you’re using). This allows you to have multiple terminal commands and applications running side by side without the need to open multiple terminal emulator windows.
