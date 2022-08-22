# Openings

Experimenting with scraping job openings from the web.

# Prerequisites

- Python 3.10
- pip/conda installed

# Installing

Create a conda env and install requirements. You can do this by running

```bash
conda create --prefix env python
conda activate ./env
pip install -r requirements
```

# Running spiders

There is one spider for Recruitee.

To run a recruitee spider, run:
```bash
scrapy runspider jobscrapper/spiders/recruitee.py
```

All jobs will be stored under `data/`, on a separate file per company.