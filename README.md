# Setupkali
Setting up the Kali Linux for OSCP

Download the Kali Virtual box for windows

1) Install the foxyproxt and required plugin for Firefox
2) Set up the display, session timeout, and other os settings
3) pimpmykali.sh install download from GitHub
4) Take a snapshot of this VM
5) Prepare the tmux (refer to the tmux file)
    i) Refer to the .tmux.conf (create this file using vim under the root directory)
   ii) Create a new session tmux new -s [session_name]
       test cnt+a, I bottom colour change and show the current date and time
   iii) Close the tmux-logging
        sudo git clone https://github.com/tmux-plugins/tmux-logging /opt/tmux-logging
   iv) tmux source-file ~/.tmux.conf
           Then press Ctrl+A+Shift+P, which shows the logging info at the bottom of the screen. LS comment shows the logging file in the HOME dir
    v) Tmux ls if it's not loaded
       tmux new -s [session_name]
       tmux attach
       [To rename] Ctrl+A+,
       [To create new tab] ctrl+A, c
       [ To move b/w tabs] Ctrl+A,#
       [To Split pane vertically] Press  Ctrl+A, Ctrl+% (Ctrl+Shift+5)
       [To Split pane Horizontally] Press  Ctrl+A, Ctrl+" (Ctrl+Shift+5)
       [To close pane] EXIT, Press  Ctrl+A+X
6) Download and install
       Download the appImage
       navigate to download folder
       Change the permission executable
       sudo chmod +x obsidian-1.x.x.AppImage
       ./obsidian-1.x.x.AppImage --no-sandbox
       Crate the Vault and choose the folder
