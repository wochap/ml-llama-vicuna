# ML LLama Vicuña

## Setup

```sh
$ conda env create -f environment.yml
$ conda activate ml-llama-vicuna
$ python src/data/download.py
```

Im on mac and everything doesnt work until i run:

```sh
$ conda install -c pytorch -c fastai fastai jupyter
```

Every time you update `environment.yml`, run:

```sh
$ conda env update -f environment.yml
```

## Development

```sh
$ jupyter lab     
```

## Resouces

- [Project Structure](https://towardsdatascience.com/structure-and-automated-workflow-for-a-machine-learning-project-2fa30d661c1e)


## Images

```
urls=Array.from(document.querySelectorAll('.rg_i')).map(el=> el.hasAttribute('data-src')?el.getAttribute('data-src'):el.getAttribute('data-iurl'));
urls = Array.from(document.querySelectorAll('.tile--img__img')).map(el => el.getAttribute('data-src'))
window.open('data:text/csv;charset=utf-8,' + escape(urls.join('\n')));
```
