# JsonDsl jupyter notebook with some examples

Created to be used as demo material at the March 2024 Kotlin meetup in Berlin for my presentation on [json-dsl](https://github.com/jillesvangurp/json-dsl).

What's JsonDsl?

> Create Kotlin DSLs for any JSON/YAML. JsonDsl is a library that helps you build Kotlin DSLs for JSON and YAML dialects. The DSLs are easy to extend with custom fields by users via a MutableMap. This allows your DSL users to work around any features you don't have in your DSL.

## Usage

Install Jupyter and the then kotlin-jupyter-kernel. If you use miniconda, this is how you can do it:

```shell
conda create --name kotlin-jupyter python=3.12
conda activate kotlin-jupyter
conda install jupyter
conda install -c jetbrains kotlin-jupyter-kernel
```

## Running

Clone this repository and then in the root directory run:

```
jupyter notebook
```

Your browser should open with a list of notebooks, open the jsdon-dsl examples one.
