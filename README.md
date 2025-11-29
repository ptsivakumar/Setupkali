# Setupkali
Setting up the Kali Linux for OSCP

Download the Kali Virtual box for windows

1) Install the foxyproxt and required plugin for Firefox
2) Set up the display, session timeout, and other os settings
3) pimpmykali.sh install download from GitHub
4) Take a snapshot of this VM
5) Prepare the tmux (refer to the tmux file)
    i) Refer the .tmux.conf (create this file using vim under the root directory)
   ii) Create a new session tmux new -s [session_name]
       test cnt+a,i bottom clor change and show the current date and time
   iii) Clode the tmux-logging
        sudo git clone https://github.com/tmux-plugins/tmux-logging /opt/tmux-logging
   iv) 
