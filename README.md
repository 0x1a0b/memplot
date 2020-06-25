# memplot

A small utility written in golang to quickly plot memory usage of processes.
Still in a very early stage.
`memplot` constantly samples memory usage of a process, for a given 
duration of time and then outputs a .png file. Painless and straightforward.

## Installation
```
go get -u -v github.com/0x0f0f0f/memplot/cmd
```

## Usage
```
Usage of memplot:
  -dur duration
    	total profiling time (default 10s)
  -pid int
    	pid of the process to analyze (default -1)
  -sd duration
    	sample size in time (default 5ms)
  -vsz
    	plot virtual size
```

## Example Plot 
![](https://raw.githubusercontent.com/0x0f0f0f/memplot/master/plot.png)