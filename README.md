# Data Engineering Task

The goal of this project is to showcase Python and SQL skills. Due to time constraints, I opted to use PySpark and Jupyter without a Docker container, managing the dependecies with [Poetry](https://python-poetry.org/). I also opted for a minimal approach for data modeling, based on two tables:

1. events: raw events data from apifootball (fact table)
2. teams: columns team_id and team_name (dimension)

This data model was sufficient for developing simple and readable queries which are available in the [task](task.ipynb) notebook.

To install the dependencies and launch the Jupyter Lab environment, run:

```
poetry install
poetry shell
jupyter lab
```