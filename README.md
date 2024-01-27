### How to Manage Python Environment using Conda

#### Download and Install Anaconda

[https://repo.anaconda.com/archive/](https://repo.anaconda.com/archive/) 


#### Open anaconda CMD

**1. Init conda to run conda command on your shell (bash, fish, tcsh, xonsh, zsh, powershell)**
```
	conda init <your_shell>
```

*Example:*
```
	conda init bash
```


**2. Create new environment**
```
	conda create -n <your_environment_name> python=<your_python_version>
```
*Example:*
```
	conda create -n nhdinh39 python=3.9
```


**3. Activate environment**
```
	conda activate <your_environment_name>
```
*Example:*
```
	conda activate nhdinh39
```

**4. Install Dependencies Package (After activate environment)**
```
	python.exe -m pip install -r requirements.txt
```


**5. Deactivate environment**
```
	conda deactivate
```
*Or*
```
	conda activate base
```


**6. List all enviroment**
```
	conda env list
```


**7. Delete environment**
```
	conda remove -n <your_environment_name> --all
```
*Example:*
```
	conda remove -n nhdinh39 --all
```

#### Reference

[https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

---

