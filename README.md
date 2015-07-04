# syntax highlighter for syslog-ng configuration file

This package provides syntax highlighting for syslog-ng configuration file in Atom editor.

# How to install
 * The package can be install with the following command
```bash
apm install language-syslog-ng
```

# Features
* Yet syntax highlighter can highlight only the following syntax elements.
    * **Top level statements**: for example
```bash
options
source
filter
template
rewrite
parser
destination
log
```
    * **Top level statement names**: for example
```bash
s_file
d_net
```
    * **Driver statements**: for example
```bash
file
pipe
program
```
    * **Double quoted strings**: for example
```bash
"/tmp/input_file"
```
    * **Comments**: for example
```bash
# source elements
# destination elements
```
