- **[Install python3.6](https://askubuntu.com/a/865569)**

    ```
    $sudo add-apt-repository ppa:deadsnakes/ppa
    $sudo apt-get update
    $sudo apt-get install python3.6
    ```

- **[Prepare virtual environment](https://github.com/abawchen/cheatsheet/tree/master/python#virtual-environment)**

    ```
    $sudo pip install virtualenv
    $sudo pip install virtualenvwrapper
    ```
    ```
    export WORKON_HOME=$HOME/.virtualenvs
    source /usr/local/bin/virtualenvwrapper.sh
    ```


- **[Install labelme](https://github.com/wkentaro/labelme#ubuntu)**

    ```
    sudo apt-get install python3-pyqt5 pyqt5-dev-tools  # PyQt5
    sudo pip3 install labelme
    ```

