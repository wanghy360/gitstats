# gitstats

## Decription

```bash
Usage: gitstats [options] <gitpath..> <outputpath>

Options:
-c key=value     Override configuration value

Default config values:
{'project_name': '', 'processes': 8, 'max_domains': 10, 'commit_begin': '', 'max_ext_length': 10, 'commit_end': 'HEAD', 'linear_linestats': 1, 'style': 'gitstats.css', 'max_authors': 20, 'authors_top': 5, 'start_date': ''}

```

## Example

```bash
./gitstats -c start_date=2021-1-1 ~/repository ~/gen
./gitstats -c start_date=2021-1-1 -c filter_authors=Jack,Alice ~/repository ~/gen
```

## View result

Open in `<outputpath>`(such as ~/gen) and browse`index.html`.

