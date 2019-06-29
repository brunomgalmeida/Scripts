# README

1. Install

    ```sh
    curl --silent -k https://raw.githubusercontent.com/brunomgalmeida/Scripts/master/ssh-wrapper/ssh-wrapper | sudo tee /usr/local/bin/ssh-wrapper
    sudo chmod +x /usr/local/bin/ssh-wrapper
    printf "alias ssh='ssh-wrapper'" | tee -a $HOME/.bashrc

    curl --silent -k https://raw.githubusercontent.com/brunomgalmeida/Scripts/master/ssh-wrapper/scp-wrapper | sudo tee /usr/local/bin/scp-wrapper
    sudo chmod +x /usr/local/bin/scp-wrapper
    printf "alias scp='scp-wrapper'" | tee -a $HOME/.bashrc

    source $HOME/.bashrc
    ```

## Debug

Use: $ `ssh -v -G`
