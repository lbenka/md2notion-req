# setup with fix

```sh
# create virtual env 
python3.9 -m venv .venv

# activate the env
source ./venv/bin/activate

# install pip-tools to compile requirements
pip install pip-tool

# created requirements with fix package from git+https://github.com/jamalex/notion-py.git@refs/pull/294/merge

# create requirement.txt 
pip-compile requirements.in

# install all dependencies
pip install -r requirements.txt 
```
