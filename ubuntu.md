## [Apache2](https://www.cyberciti.biz/faq/ubuntu-linux-start-restart-stop-apache-web-server/)

```
$ sudo service apache2 restart|stop|start
```

## Python Stuff

- [Install python3.6](https://askubuntu.com/a/865569)

    ```
    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt-get update
    sudo apt-get install python3.6
    sudo apt-get install python-pip
    ```

- [Prepare virtual environment](https://github.com/abawchen/cheatsheet/tree/master/python#virtual-environment)

    ```
    sudo pip install virtualenv
    sudo pip install virtualenvwrapper
    ```
    ```
    export WORKON_HOME=$HOME/.virtualenvs
    source /usr/local/bin/virtualenvwrapper.sh
    ```


- [Install labelme](https://github.com/wkentaro/labelme#ubuntu)

    ```
    sudo apt-get install python3-pyqt5 pyqt5-dev-tools  # PyQt5
    sudo pip3 install labelme
    # pip install https://github.com/abawchen/labelme.git
    ```

- Trouble shooting

    * [mysql.c:32:20: fatal error: Python.h: No such file or directory](https://github.com/openai/gym/issues/757#issuecomment-338700681)
    
    
        ```
        sudo apt-get install python3.6-dev libmysqlclient-dev
        ```
    
    
## Node Stuff

- Install npm

    ```
    sudo apt-get install python-software-properties
    sudo add-apt-repository ppa:gias-kay-lee/npm
    sudo apt-get update
    sudo apt-get install npm
    ```

## Mount

```
echo $UID # to get current user's uid
sudo mount -o username="username",password="password",uid=uid //ip/folder /mntdest
```
