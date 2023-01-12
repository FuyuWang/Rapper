# Rapper

Rapper a deep reinforcement learning-based DNN mapper, 
to search the optimized mapping strategies for spatial accelerators.
This repository contains the source code for Rapper.

### Setup ###
* Download the Rapper source code
* Create virtual environment through anaconda
```
conda create --name RapperEnv python=3.8
conda activate RapperEnv
```
* Install packages
   
```
pip install -r requirements.txt
```

* Install [MAESTRO](https://github.com/maestro-project/maestro.git)
```
python build.py
```

### Run Rapper ###

* Run RL-based mapping search of Rapper on TPU
```
./run_tpu.sh
```

* Run RL of mapping search Rapper on Eyeriss
```
./run_eyeriss.sh
```

* Run GA-based improvement of Rapper
```
./run_ga.sh
```


