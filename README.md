# Vsc-in-replit
How to use vsc in replit 
# Follow the steps given below

Create a replit project in bash

Copy the code given below to main.sh file

```yaml
if [[ ! -d code-server-3.12.0-linux-amd64 ]]
then
    wget https://github.com/cdr/code-server/releases/download/v3.12.0/code-server-3.12.0-linux-amd64.tar.gz
    tar xvzf code-server-3.12.0-linux-amd64.tar.gz
fi

cd code-server-3.12.0-linux-amd64/bin

./code-server --bind-addr 0.0.0.0:8080 --auth password
```

All over, run the project, and go to the provided website
Note To work fast with vsc in replit you need hacker plan Also replit doest keep data, it changes every 12 hours so restart you replit after use
