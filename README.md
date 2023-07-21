# Datafold VSCode Extension Demo: Data Diffs

This is a demo for how to use the [Datafold VSCode Extension](https://marketplace.visualstudio.com/items?itemName=Datafold.datafold-vscode&ssr=false#overview) to compare data between your development and production environments with [dbt](https://www.getdbt.com/).

TODO: add a link to the blog post


### Let's get started!

Copy and paste the below in your terminal to get started with this demo in a single motion.

```shell
python3 -m venv venv # setup your virtual environment
source venv/bin/activate # activate it
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
source venv/bin/activate
dbt build
dbt build --target prod
data-diff --dbt
```

> Note: the rest of this is the original README.md file from the dbt-labs/jaffle_shop_duckdb repo
