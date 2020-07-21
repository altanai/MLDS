# DataScience

## install Anaconda 

conda inatall anaconda-client
```
➜  anaconda3 sudo bin/conda install anaconda-client
[sudo] password for altanai: 
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/altanai/anaconda3

  added / updated specs:
    - anaconda-client


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    conda-4.8.3                |           py37_0         2.8 MB
    ------------------------------------------------------------
                                           Total:         2.8 MB

The following packages will be UPDATED:

  conda                                        4.8.2-py37_0 --> 4.8.3-py37_0


Proceed ([y]/n)? y


Downloading and Extracting Packages
conda-4.8.3          | 2.8 MB    | ################################################################################################################################################################# | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```

install anaconda-navogator
```
➜  anaconda3 sudo bin/conda install anaconda-navigator
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/altanai/anaconda3

  added / updated specs:
    - anaconda-navigator


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    anaconda-navigator-1.9.12  |           py37_1         4.4 MB
    ------------------------------------------------------------
                                           Total:         4.4 MB

The following packages will be UPDATED:

  anaconda-navigator                          1.9.12-py37_0 --> 1.9.12-py37_1


Proceed ([y]/n)? y


Downloading and Extracting Packages
anaconda-navigator-1 | 4.4 MB    | ################################################################################################################################################################# | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```

## create Virtual Env 

conda create --name <name> python=3.5
  
or with pandas 
conda create --name <name> python=3.5 panda

or with entore anaconda lib
conda create --name <name> python=3.5 anaconda

```
➜  MLDS git:(master) ~/anaconda3/bin/conda create --name snowflakes biopython
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /home/altanai/anaconda3/envs/snowflakes

  added / updated specs:
    - biopython


The following packages will be downloaded:

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
```

see all env 
```
➜  MLDS git:(master) ~/anaconda3/bin/conda info --envs        
# conda environments:
#
base                  *  /home/altanai/anaconda3
snowflakes               /home/altanai/anaconda3/envs/snowflakes
```
Procced to activate or deactivate 


ref : https://docs.anaconda.com/anaconda-cloud/user-guide/getting-started/#finding-downloading-and-installing-packages
