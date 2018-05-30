# PandocWriterTikiWiki
A pandoc custom writer for TikiWiki syntax

## Usage

* [Install pandoc](https://pandoc.org/installing.html)
* Specify the location of the `tikiwiki.lua` as a parameter for `-t`. For example:

   ```bash
   pandoc -f markdown -t tikiwiki.lua test.md
   ```
