# Monte Carlo Simulations
This repo contains Jupyter notebooks and data on Monte Carlo Simulations for Firemark Labs Thirsty Thursday Session on 15th Dec 2022. It comprises two examples where Monte Carlo is applied.

---
# To Run
## Prerequisites:

- Have docker installed locally 
- Check GitHub repo access https://github.com/julianaddison/fm-thirstyThursday-monteCarlo
- Check Confluence page access https://confluence.iag.com.au/display/FMSG/Monte+Carlo+Simulations


### Setting Up

- Git clone https://github.com/julianaddison/fm-thirstyThursday-monteCarlo or fork the repo into your GitHub account 
- From the directory where the project is cloned, run the docker command below

``` bash
docker run -v PWD:/home/jovyan -p 9999:8888 -it -e JUPYTER_ENABLE_LAB=yes jupyter/datascience-notebook:latest
```

- Go to localhost:9999 in your browser
