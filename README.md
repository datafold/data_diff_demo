# Datafold VSCode Extension Demo: Data Diffs

This is a demo for how to use the [Datafold VSCode Extension](https://marketplace.visualstudio.com/items?itemName=Datafold.datafold-vscode&ssr=false#overview) to compare data between your development and production environments with [dbt](https://www.getdbt.com/).

TODO: add a link to the blog post


### Let's get started!

Copy and paste the below in your terminal to get started with this demo in a single motion.

```shell
python3 -m venv venv # setup your virtual environment
source venv/bin/activate # activate it
python3 -m pip install --upgrade pip # upgrade pip
python3 -m pip install -r requirements.txt # install dbt and data-diff
source venv/bin/activate # reactivate virtual environment
dbt build # build development datasets
dbt build --target prod # build production datasets
data-diff --dbt # run data-diff CLI to compare development and production datasets
```

