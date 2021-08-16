# DataScience

## Scikit 

Scikit-learn is an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection and evaluation, and many other utilities.

    python3 -m pip show scikit-learn

Import learn packages

    python3 -c "import sklearn; sklearn.show_versions()"

    System:
        python: 3.6.9 (default, Jan 26 2021, 15:33:00)  [GCC 8.4.0]
    executable: /usr/bin/python3
      machine: Linux-4.15.0-136-generic-x86_64-with-Ubuntu-18.04-bionic

    Python dependencies:
              pip: 21.1.1
      setuptools: 56.1.0
          sklearn: 0.24.2
            numpy: 1.19.2
            scipy: 1.5.2
          Cython: None
          pandas: 1.0.5
      matplotlib: 3.3.1
          joblib: 0.16.0
    threadpoolctl: 2.1.0

    Built with OpenMP: True

  

## Anaconda 
installing anaconda

  conda inatall anaconda-client

    ➜  anaconda3 sudo bin/conda install anaconda-client
    Collecting package metadata (current_repodata.json): done
    Solving environment: done

    environment location: /home/altanai/anaconda3
    added / updated specs:
      - anaconda-client

      package                    |            build
      ---------------------------|-----------------
      conda-4.8.3                |           py37_0         2.8 MB
      ------------------------------------------------------------
                                              Total:         2.8 MB

  install anaconda-navigator

    ➜  anaconda3 sudo bin/conda install anaconda-navigator
    Collecting package metadata (current_repodata.json): done
    Solving environment: done

    environment location: /home/altanai/anaconda3

    added / updated specs:
      - anaconda-navigator

      package                    |            build
      ---------------------------|-----------------
      anaconda-navigator-1.9.12  |           py37_1         4.4 MB
      ------------------------------------------------------------
                                            Total:         4.4 MB

## create Virtual Env 

    conda create --name <name> python=3.5
  
or with pandas 

    conda create --name <name> python=3.5 panda

or with anaconda lib
    
    conda create --name <name> python=3.5 anaconda

    ➜  MLDS git:(master) ~/anaconda3/bin/conda create --name snowflakes biopython
    Collecting package metadata (current_repodata.json): done
    Solving environment: done

    environment location: /home/altanai/anaconda3/envs/snowflakes

    added / updated specs:
      - biopython

    package                    |            build
    ---------------------------|-----------------
    biopython-1.77             |   py38h7b6447c_0         2.1 MB
    ca-certificates-2020.6.24  |                0         125 KB
    certifi-2020.6.20          |           py38_0         156 KB
    intel-openmp-2020.1        |              217         780 KB
    libedit-3.1.20191231       |       h14c3975_1         116 KB
    libffi-3.3                 |       he6710b0_2          50 KB
    mkl-2020.1                 |              217       129.0 MB
    mkl-service-2.3.0          |   py38he904b0f_0          62 KB
    mkl_fft-1.1.0              |   py38h23d657b_0         150 KB
    mkl_random-1.1.1           |   py38h0573a6f_0         341 KB
    ncurses-6.2                |       he6710b0_1         817 KB
    numpy-1.18.5               |   py38ha1c710e_0           5 KB
    numpy-base-1.18.5          |   py38hde5b4d6_0         4.1 MB
    openssl-1.1.1g             |       h7b6447c_0         2.5 MB
    pip-20.1.1                 |           py38_1         1.7 MB
    python-3.8.3               |       hcff3b4d_2        49.1 MB
    readline-8.0               |       h7b6447c_0         356 KB
    setuptools-49.2.0          |           py38_0         737 KB
    six-1.15.0                 |             py_0          13 KB
    sqlite-3.32.3              |       h62c20be_0         1.1 MB
    tk-8.6.10                  |       hbc83047_0         3.0 MB
    wheel-0.34.2               |           py38_0          51 KB
    xz-5.2.5                   |       h7b6447c_0         341 KB
    ------------------------------------------------------------
                                           Total:       196.7 MB

see all env 

    ➜  MLDS git:(master) ~/anaconda3/bin/conda info --envs        
    # conda environments:
    #
    base                  *  /home/altanai/anaconda3
    snowflakes               /home/altanai/anaconda3/envs/snowflakes

Procced to activate or deactivate 


**References**  : 
- https://docs.anaconda.com/anaconda-cloud/user-guide/getting-started/#finding-downloading-and-installing-packages
- https://scikit-learn.org/stable/install.html#installation-instructions 
