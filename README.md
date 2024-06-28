## 1. Crateating vituarl env in Poetry.
```
- poetry new project_name
- poetry new my-folder --name my-package

- poetry add package_name
- poetry remove package_name
```

## 2. Creating virtual env on default path.
```
- poetry env info
- potry install 
c:\Users\AppData\Local\pypoetry\Cache\virtualenvs\src-NAqrsk9Z-py3.12
```

## Crateing vitual env on inside the project.

1. Find path of env  
    - poetry env info -p // go and delete this directory.
2.L ets change poetry setting.
    - poetry config virtualenvs.in-project true
3. Lets create a new virtual env.
    - poetry intall
4. Use poetry in shell.
    - poetry shell
    - Now you can install dipendency 
5. Exit.
    - exit
    - deactivate
