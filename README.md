# Robust Journey Planning
##### Guarin Fluck, Emilio Fernández, Hiroki Hayakawa, Xiangyu Tian  

In this project, we developed a robust journey planner for Swiss public transport network in the city of Zurich. In other words, we tried to build our own custom "Google Maps" but also taking probability of delay into account for prioritasing the less delayed connections. The detailed task description can be found in [project_description](project_description.md) whereas [final_notebook](notebooks/final_notebook.ipynb) explains the structure of the project. A short video presenting the final solution can be found [here](https://www.youtube.com/watch?v=tZWT6d0ZCrg&feature=youtu.be).

---
**Installation setup**
```
conda env create -f local_environment.yml
jupyter labextension install @pyviz/jupyterlab_pyviz
```

If there are any issues run:
```
conda env create -f local_environment_export.yml
jupyter labextension install @pyviz/jupyterlab_pyviz
```

---

**Journey Planner Interface**
![](images/journey_planner.png)

**Journey Visualization**
![](images/journey_visualization.png)
