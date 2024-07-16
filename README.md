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
- poetry install 
c:\Users\AppData\Local\pypoetry\Cache\virtualenvs\src-NAqrsk9Z-py3.12
```

## Creating virtual env inside the project.

1. Find the path of virtual env  
    - poetry env info -p // go and delete this directory.
2. Let's change the poetry setting.
    - `poetry config virtualenvs.in-project true`
3. Let's create a new virtual env.
    - poetry install
4. Use poetry in shell.
    - poetry shell
    - Now you can install dependency
5. Installing Dev dependencies
    - poetry add python-dotenv@latest --group dev
6. Exit.
    - exit
    - deactivate
