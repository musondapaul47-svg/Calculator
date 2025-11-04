# how to run
the following are instructions on how to run the project
## things needed befeore you run
* uv(have uv installed)
* python
* tkinter
* an editor
## steps to get packages
1. enter the project directory after cloning using cd 
```bash
cd <project-directory>
```
2. download all packages using `uv sync`
example

```bash
uv sync
```
3. to run use the `uv-run`
e.g

```bash
uv run main.py --help
```
## some commands

to check version
```bash
uv run main.py version
```
to divide 
```bash
uv run main.py divide 5 6
```
to multiply 
```bash
uv run main.py multiply 5 6
```
