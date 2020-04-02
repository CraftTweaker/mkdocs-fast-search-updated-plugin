# Mkdocs fast search updated

Mkdocs plugin to exclude tables and code from the search_index.json as it can be unwanted and lead to huge indexes

## Installation

```bash
pip install git+https://github.com/CraftTweaker/mkdocs-fast-search-updated-plugin.git
```


## Usage

In your `mkdocs.yml` file add `use-site-url` to the plugins entry:

```yaml
plugins:
  - fast-search-updated
```