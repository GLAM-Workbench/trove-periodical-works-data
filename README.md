# trove-periodical-works-data

A GLAM Workbench dataset

These datasets were generated using notebooks in the [trove-journals](https://github.com/GLAM-Workbench/trove-journals/) repository.

For more information and documentation see the [CSV formatted list of journals available from Trove in digital form](https://glam-workbench.net/trove-journals/csv-digital-journals/) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [periodical-works.csv](https://github.com/GLAM-Workbench/trove-periodical-works-data/raw/main/periodical-works.csv) (612.6 kB, text/csv)


## Dataset details

### [periodical-works.csv](https://github.com/GLAM-Workbench/trove-periodical-works-data/raw/main/periodical-works.csv)

|                |                                                                                                                                                                                                                                                           |
|:---------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-03-13                                                                                                                                                                                                                                                |
| file size      | 612.6 kB                                                                                                                                                                                                                                                  |
| format         | text/csv                                                                                                                                                                                                                                                  |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-journals/blob/master/Create-digitised-journals-list.ipynb'>Create a list of Trove's digital periodicals</a> ([documentation](https://glam-workbench.net/trove-journals/create-list-digitised-journals/)) |
| number of rows | 930                                                                                                                                                                                                                                                       |
| description    | This dataset contains version records describing digitised periodicals found by searching for the digital identifier string `nla.obj` and limiting the results to periodicals. Duplicate records were merged.                                             |

#### Columns

| name                | type   | description                                                                              |
|:--------------------|:-------|:-----------------------------------------------------------------------------------------|
| `fulltext_url`      | string | link to digitised viewer                                                                 |
| `title`             | string | title of the periodical; multiple values separated by | symbol                           |
| `work_url`          | string | link to work record in Trove; multiple values separated by | symbol                      |
| `work_type`         | string | Trove work format, eg: 'Book'; multiple values separated by | symbol                     |
| `contributor`       | string | multiple values separated by | symbol                                                    |
| `publisher`         | string | multiple values separated by | symbol                                                    |
| `date`              | string | multiple values separated by | symbol                                                    |
| `type`              | string | eg: 'text'; multiple values separated by | symbol                                        |
| `format`            | string | eg: 'volume'; multiple values separated by | symbol                                      |
| `extent`            | string | size or physical dimensions; multiple values separated by | symbol                       |
| `language`          | string | publication language; multiple values separated by | symbol                              |
| `subject`           | string | associated subject headings; multiple values separated by | symbol                       |
| `spatial`           | string | nan                                                                                      |
| `is_part_of`        | string | collections or series this publication is part of; multiple values separated by | symbol |
| `identifier`        | string | library identifiers; multiple values separated by | symbol                               |
| `rights`            | string | copyright and licensing information; multiple values separated by | symbol               |
| `fulltext_url_text` | string | text of link to digitised book viewer                                                    |
| `catalogue_url`     | string | link to NLA catalogue; multiple values separated by | symbol                             |## Examples of use



----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)