## How big is the dataset?
The file is 4.7 MB
```bash
ls -l clean_dialog.csv
```
The file contains 36860 rows
```bash
wc -l clean_dialog.csv
```
## Structure of the data
The fields are "Title", "Writer", "Pony" and "Dialog"
```bash
head -1 clean_dialog.csv
```
## How many episodes covered?
There are 197 episodes covered
```bash
csvtool col 1 data.csv | tail -n +2 | sort | uniq | wc -l
```
## Unexpected aspect
There are annotations with brackets.## How big is the dataset?
The file is 4.7 MB
```bash
ls -l clean_dialog.csv
```
The file contains 36860 rows
```bash
wc -l clean_dialog.csv
```
## Structure of the data
The fields are "Title", "Writer", "Pony" and "Dialog"
```bash
head -1 clean_dialog.csv
```
## How many episodes covered?
There are 197 episodes covered
```bash
csvtool col 1 data.csv | tail -n +2 | sort | uniq | wc -l
```
## Unexpected aspect
There are annotations with brackets.
