# priority-order-decision
## Python Program to order your tasks

### Donwload & Run

```sh 
git clone https://github.com/fackelm2/priority-order-decision
cd priority-order-decision
prorityorder
```

### Usage Guide
<pre>
usage: priority-order-decision.py [-h] [-i INPUT_FILE] [-o OUTPUT_FILE] [-f {text,csv,html}] [-d] [-v] [--version] mytask [mytask ...]

Options for command-line tool priority-order-decision.py

positional arguments:
  mytask                list of tasks space separeted or filename [-i <filename>] with one task per line

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT_FILE, --input_file INPUT_FILE
                        set input filename
  -o OUTPUT_FILE, --output_file OUTPUT_FILE
                        set output filename (default <console>)
  -f {text,csv,html}, --output_format {text,csv,html}
                        set output format (default <text>)
  -d, --debug           set debug mode
  -v, --verbose         set verbose mode
  --version             print version

</pre>

### priorityorder.py program tasks

```sh 
input
working tasks (a, b, c, d, e, f, g)

## process
program ask for your priority (for example: a or b) for each entry

## output
order of working tasks with your priority (for example : e, b, c, a, f, g, d)
```

### Examples
<pre>
<b> ||   |  </b>
<b> | |  |  </b>
<b> |  | |    </b>
<b> |   ||    </b>
