# This repo was made as an use case of both Nixtla's Neural Forecast and Ploomber example
First, Neural Forecast.ipynb was written separately, and then Ploomber's Soorgeon automatically generated everything else using 
```sh
soorgeon refactor .\Neural Forecast.ipynb
```
This is the last text added to the defaultly generated README made by Soorgeon, so on to what Soorgeon did:

# This pipeline was automatically generated

## Setup

```sh
pip install -r requirements.txt
```

## Usage

List tasks:

```sh
ploomber status
```

Execute:

```sh
ploomber build
```

Plot:

```sh
ploomber plot
```

*Note:* plotting requires `pygraphviz` for instructions, [see this.](https://docs.ploomber.io/en/latest/user-guide/faq_index.html#plotting-a-pipeline)

## Resources

* [Ploomber documentation](https://docs.ploomber.io)
