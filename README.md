# Vsc-in-replit
How to use vsc in replit 
# Follow the steps given below

Create a replit project in bash

Copy the code given below to main.sh file

`if [[ ! -d code-server-3.12.0-linux-amd64 ]]
then
    wget https://github.com/cdr/code-server/releases/download/v3.12.0/code-server-3.12.0-linux-amd64.tar.gz
    tar xvzf code-server-3.12.0-linux-amd64.tar.gz
fi

cd code-server-3.12.0-linux-amd64/bin

./code-server --bind-addr 0.0.0.0:8080 --auth password`
