    sudo apt update -y
    sudo apt upgrade -y
    sudo apt install python3-pip python3-setuptools -y
    
    
    sudo pip3 install pip -U setuptools
    sudo pip3 install apache-airflow==2.2.0
    PATH=$PATH:$(pwd)/.local/bin
    
 
    
    # airflow db init
    # airflow users create -u admin -f ken -l chan -r Admin -e chankamlam@icloud.com -p Ken5201314
    # airflow webserver -p 8080 -D && airflow scheduler -D
    # pip3 install "apache-airflow[kubernetes]"
