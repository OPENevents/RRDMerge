# RRDMerge

RRDMerge is a tool developped by OPENevents to merge multiple RRD file with input/output datasources.


## Installation

* Install php5, php5-rrd

`apt-get update && apt-get install php5 php5-rrd`

* Add RRDMerge in your `$PATH`

`mv RRDMerge /usr/local/bin/`

`chmod 755 /usr/local/bin/RRDMerge`


## Usage

```
RRDMerge --start=<timestamp> --end=<timestamp> --source=</path/to/file1.rrd,/path/to/file2.rrd...> --output=</path/to/file_merged.rrd> [OPTIONS]

Options :
    --start     Start time
    --end       End time
    --source    Path to RRD files
    --output    Path to RRD file merged
    --verbose   Verbose
    --help      Show help for RRDMerge
```


