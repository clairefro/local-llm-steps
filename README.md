# local-llm-steps

1. use python virtual env (https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

python3 -m venv .env

2. activate virtual env

source env/bin/activate (deactivate: "deactivate" or "exit")

3. if get SSL error, manuall set the venv urllib3 version to 1.26.6

pip install urllib3==1.26.6

install pytorch w/ pip https://pytorch.org/get-started/locally/
