# tmuxProject

A small shell script function called npt (new pentest in tmux) that allows to create tmux sessions with pre defined windows, panes and commands. Also, all panes are logged with the command script (which is called using a second function) so you can have a complete history of everything you do in all terminals.  

The main idea here is to use this when you are working on a large project that demands a lot of terminals, which requires a nice level of organization so you don't lose track of your work and also logs everything that's being done.  

Put these functions in your .bashrc|.zshrc file and then:  
`source <.bashrc|.zshrc>`
