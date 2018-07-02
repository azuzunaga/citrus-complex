# Installation instructions
### Install python3
`brew install python3`

### Install virtualenv
`pip3 install virtualenv`

### User virtualenv to create a workspace
```bash
cd [PROJECT_DIR]/citrusComplex
virtualenv ve
. ve/bin/activate
```

### While still in the directory, install django, and start the server
```bash
pip3 install django
python3 manage.py startserver
```
Navigate to ![url](http://127.0.0.1:8000/polls)
