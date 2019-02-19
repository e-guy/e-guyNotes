# Summary of setting-up virtualenv

### preparation
  (make sure python installed in your ubuntu system, the installed packages may be found at /usr/bin/python2.7 or /usr/bin/python3.5) 
  ```
  $ pip install virtualenv
  $ mkdir ~/py_venv && cd ~/py_venv
  ```  
 
### create venv
  ```
  $ virtualenv -p /usr/bin/python2.7 --no-site-packages py2.7venv
  ```  
  (if python3.5 is expected for your venv, change to /usr/bin/python3.5, and give the venv a name e.g py3.5venv)

### activate venv
  ```
  $ source py2.7venv/bin/activate
  (py2.7venv) $ 
  ```  

### check venv
  ```
  $ python -V
  ```  

### deactivate venv
  ```
  (py2.7venv) $ deactivate
  ``` 

