# README

1. Install

    ```sh
    curl -k https://raw.githubusercontent.com/brunomgalmeida/Scripts/master/ssh-wrapper/ssh-wrapper | sudo tee -a /usr/local/bin/ssh-wrapper
    printf "alias ssh='ssh-wrapper'" | tee -a $HOME/.bashrc

    curl -k https://raw.githubusercontent.com/brunomgalmeida/Scripts/master/ssh-wrapper/scp-wrapper | sudo tee -a /usr/local/bin/scp-wrapper
    printf "alias scp='scp-wrapper'" | tee -a $HOME/.bashrc

    source $HOME/.bashrc
    ```